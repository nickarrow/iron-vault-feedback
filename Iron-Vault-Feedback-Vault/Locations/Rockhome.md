# Settlement - Rockhome

```mechanics
oracle-group name="Settlement Oracles: New Settlement Oracles" {
    oracle name="[Settlement Oracles \/ Settlement Projects](oracle:starforged\/oracles\/settlements\/projects)" result="Agriculture" roll=2
    oracle name="[Settlement Oracles \/ Location](oracle:starforged\/oracles\/settlements\/location)" result="Orbital" roll=47
}
```

We need a planet for Rockhome since it is in orbit. Let’s generate one:
```mechanics
oracle name="[Planet Oracles \/ Planetary Class](oracle:starforged\/oracles\/planets\/class)" result="[Grave World](id:starforged\/collections\/oracles\/planets\/grave)" roll=33
```
Grave world, ok, we need a name for it. 
```mechanics
oracle name="[Planet Oracles \/ Grave World \/ Sample Names](oracle:starforged\/oracles\/planets\/grave\/name)" result="Anubis" roll=1
```
That’s a bit on the nose, how about we just call it [[Abis Prime]]. 
