# Settlement Nyx
```mechanics
oracle-group name="Settlement Oracles: New Settlement Oracles" {
    oracle name="[Settlement Oracles \/ Settlement Projects](oracle:starforged\/oracles\/settlements\/projects)" result="Migration" roll=51
    oracle name="[Settlement Oracles \/ Location](oracle:starforged\/oracles\/settlements\/location)" result="Orbital" roll=48
    oracle name="[Settlement Oracles \/ First Look](oracle:starforged\/oracles\/settlements\/first_look)" result="Built from random scrap" roll=12
    oracle name="[Settlement Oracles \/ Authority](oracle:starforged\/oracles\/settlements\/authority)" result="Fair" roll=55
}
```

Nyx is in orbit so we need another planet. Let’s generate one:
```mechanics
oracle name="[Planet Oracles \/ Planetary Class](oracle:starforged\/oracles\/planets\/class)" result="[Ice World](id:starforged\/collections\/oracles\/planets\/ice)" roll=45
```
Ice world. Needs a name: 
```mechanics
oracle name="[Planet Oracles \/ Ice World \/ Sample Names](oracle:starforged\/oracles\/planets\/grave\/name)" result="Boreas" roll=2
```
The ice world of [[Boreas]].  