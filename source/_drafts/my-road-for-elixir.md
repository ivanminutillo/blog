---
title: La mia strada per Elixir
---

Da qualche giorno ho deciso di intraprendere lo studio di Elixir, le motivazioni sono state diverse: 
- Fino ad oggi l'unico linguaggio con cui ho lavorato è stato Javascript, senza entrare nel flame eterno, ho sentito il bisogno di imparare un nuovo linguaggio
- Il mio quinto senso e mezzo formicola quando si parla di **programmazione funzionale**, ma non sono abbastanza disciplinato - e competente - da implementarla in Javascript
- Sto valutando Elixir come linguaggio per il nuovo backend di [Agent](https://github.com/opencooperativeecosystem.net/agent)

L'idea di questo post è di riportare le risorse che mi hanno aiutato maggiormente nello studio di Elixir con un po di spiegone per ognuna.


## A monte: perchè funzionale ?

![il buon Rich Hickey](https://i.imgur.com/JBCbDXz.png)


[The value of values with Rich Hickey](https://www.youtube.com/watch?v=-6BsiVyC1kM)

> every time I watch one of his talks I feel like someone has gone in and organized my brain
> 

In questo video di 30 minuti, Rich Hickey - creatore di Clojure - fa un' introduzione alla programmazione funzionale, che anche se lentamente guadanga sempre più terreno è ancora vista come uno stile elitario o un po da frikkettoni. 

Se come me, volete approfondire il pensiero di Rich Hickey, [questa repository](https://github.com/tallesl/Rich-Hickey-fanclub) contiene una collezione di suoi talk, interviste e articoli.


## Il glossario base di Elixir
Molto facile che dopo neanche 10minuti che leggi a proposito di Elixir, che sia la guida ufficiale o un articolo sul web, sei incappato in 4-5 nomi di tools che sembrano fondamentali ma ti dicono poco o nulla. 
Facciamo un po di luce:

- **iEX**
- **mix**
- **Phoenix**
- **OTP**
- **ExUnit**

### IEx
iEx è la shell interattiva di Elixir.
La prima cosa che mi è saltata all'occhio sono stati gli helpers. 
IEx ne fornisce diversi e possono essere invocati attraverso la funzione `h(String)`, se invocata senza argomenti `h/0` restituisce una breve documentazione per muovere i primi passi con la shell, altrimenti può contenere anche un parametro `h/1`, per invocare la documentazione per qualsiasi modulo o funzione di Elixir. 
Questo è possibile perche Elixir tratta la documentazione come first class citizen. 
Ad esempio `h(Enum)` restituisce
    ```
Provides a set of algorithms that enumerate over enumerables according to the
Enumerable protocol.

    iex> Enum.map([1, 2, 3], fn(x) -> x * 2 end)
    [2, 4, 6]

Some particular types, like maps, yield a specific format on enumeration. For
example, the argument is always a {key, value} tuple for maps:

    iex> map = %{a: 1, b: 2}
    iex> Enum.map(map, fn {k, v} -> {k, v * 2} end)
    [a: 2, b: 4]

Note that the functions in the Enum module are eager: they always start the
enumeration of the given enumerable. The Stream module allows lazy enumeration
of enumerables and provides infinite streams.

Since the majority of the functions in Enum enumerate the whole enumerable and
return a list as result, infinite streams need to be carefully used with such
functions, as they can potentially run forever. For example:

    Enum.each Stream.cycle([1, 2, 3]), &IO.puts(&1)```

Non male per chi sta muovendo i primi passi in elixir uh?

### Mix
Mix è un build tool 7pòlà