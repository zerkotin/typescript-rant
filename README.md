# i-hate-typescript

ill start by saying - this is my oppinion - whether you like it or not - it remains.

## ive been using it for 2 years now
not by choice of course - it was a company decision - which im very much against.
let me say that the typing idea is not all bad - it has its perks - especially when it comes to API and code completion.
it makes life easy in some cases - and i will argue that i would have used typing to some small degree.

but! with that said - with no doubt whatsoever i would take javascript with no typing everyday.

## why do people use typescript
i think that the people who prefer typescript over javascript did not takke the time to grow on it and get used to a functional programming way.

they probably come from OO world (although i did too - but that was long ago) and cant get used to flexibility of the language. it must be scary i get it i was there, but i took the time and after many years of javascript i find it beautiful.

## how it feels to use typescript
whenever i use typescript i cant help but feel suffucated and castrated. 
clean code - forget it - it looks so ugly.
my hands want to smack the keyboard everytime i need to write a type for something that is so obvious,
write something just for the compiler to accept it
or write a function to make sure types are correct - seriously its the  worst.

## typeguards - the most horrible invention of typescript
typeguards are typescripts way of making sure a type is enforced and casted correctly.
a typeguard is a function! now - i could accept a function like that if it was for compiling only and then removed by the compiler - but those functions actually pass down to the javascript and are used.

## performance
using typescript requires
1. extra code for typing and satisfying the compiler
2. extra functions just for typing
3. it encourages OO style of writing - which in turn causes many classes to be created with no reason - which leads to more memory consumption.

you might argue about the last point - if you have good programmers it wont happen right? wrong - it happens time and time again, years of experience tought me differently.

## what is the main argument for typescript?
its better to have typing when working in large groups.
it helps with code completion.

sorry but no ... its better to have good javascript developers rather than java developers that try to do frontend in typescript.

# what is the alternative ? Well defined BEST PRACTICES and Experience
take the time to know the language intimately - embrace its flexibility.
most important!

Javascript has a huge community - there are BEST PRACTICES - take time to learn them.
this is usually the main problem.
people dont know how to approach a certain problem and "just do".
use a linter to enforce certain practices.

think and learn before you "just do" and i assure you - you wont need types.
as for code completion, the latest IDEs allow for code completion even without types, 
yes its not as comperhensible, but its good enough.


## summary
i hate typescript is a bit harsh - i dont like it for many reasons - mostly because i like my clean javascript code and i see typescript more as a disturbance rather than helpful. sure types can be nice sometimes - but for the very little times where i would have liked types - typescript is an overkill which requires more than i wish to sacrifice.

typescript can be used mildly - but from my experience developers mostly abuse the code with overtyping everyhing possible.
it looks bad, its not performant - i have nothing more to add.


## quick update
4 years later - typescript seems to have developed to be the standard.
in big projects you lose all hope of remembering and finding the right properties for objects unless you have a very good order of things.
but in big teams things often get out of hand.
in that case, having types is helpful for code completion, you need less time for searching things.

nevertheless i stand by my Rant - and i still think you can do it well wihtout typescript, and if you still choose to use it, do not use it extensively and force types on everything.
"any" is not the enemy, in fact its quite encouragable in some places in my oppinion.
if you see a case where its there because of laziness rather than code artistry, create a ticket to fix it...

"Types should be helpful and not hindering".

