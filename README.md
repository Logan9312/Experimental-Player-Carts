# Experimental Player Carts

A server-side Fabric mod for Minecraft 26.3 that gives your minecart experimental
physics while you ride it. Name a regular cart `#fast` in an anvil to give it
the same physics whether empty or occupied. Other empty carts and mob carts
keep vanilla mechanics.

```mcfunction
/gamerule minecraft:max_minecart_speed 24
```

That sets the limit to 24 blocks per second; the default is 8.

Build and run the tests with Java 25: `./gradlew build`.
