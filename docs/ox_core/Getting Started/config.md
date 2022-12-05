# Config

Resource configuration is handled using [convars](https://docs.fivem.net/docs/scripting-reference/convars/).  

```yml
# Players must have a valid identifier to join the server. Used to fetch userid from the database.
set ox:primaryIdentifier "fivem"

# Set the number of active characters a user can have registered.
setr ox:characterSlots 5

# Enables debug and development features. Should only be used in a development environment.
setr ox:debug 0

# Disable death system handle by core.
setr ox:deathSystem 0
```
