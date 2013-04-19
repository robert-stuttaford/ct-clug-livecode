# ct-clug-livecode

To live-code at Cape Town Clojure User Group meetup on 18 May

# What will we build?

A web app (I know, right?) which we'll use to vote on what topic to dive into after this live-code.

Use bootstrap for css & js.

Ring, Compojure for routing, hiccup for html generation. Datomic in-memory database for data.

Schema - :vote, :comment, :name

PAGE: Form with 2 options, web (http+routing+html) or datomic, and a textfield which allows you to say what you'd like to to see covered, a textfield for your name.

PAGE: total votes at the top. page listing votes, each with the comments for that vote. if the name starts with @, return a twitter html tag rather than just a string when rendering.
