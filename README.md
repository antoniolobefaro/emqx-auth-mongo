emqx_message_persistence_mongo
===============

EMQ X message persistence in MongoDB

in emqx 
in rebar.config add in

{deps,
    [
    ..............
    , {emqx_message_persistence_mongo,{git,"https://github.com/antoniolobefaro/emqx-message-persistence-mongo",{branch, "master"}}}
    ]}.

.......

{cloud_relx_apps,
    [
    ...........
    , {emqx_message_persistence_mongo, load}
    ]}.


