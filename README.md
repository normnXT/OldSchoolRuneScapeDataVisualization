Note on data integrity and future reuse of this data:

https://github.com/osrsbox/osrsbox-db

The original OSRSbox datasets being used have not been updated since ~2020, weapons introduced to the game after that point only have partial data that I have retrieved from the wiki, they can be found in the `missing` JSON files. The new weapons `equipment` stats, `weapon` stats, and their `wiki_url` have been updated and are correct. The new weapons are using trivial or arbitrary item ids that are not official or used in game. Stats for older weapons being used in this project (if they are in the `filtered` JSON files) have also been updated if they were rebalanced after 2020.

Due to many unusable weapons and variants like poisoned weapons, I decided to reduce available weapons data. Deciding on what group of weapons would best represent weapon stat distribution was difficult, so I reduced the data down to two groups. 

The first group contains all mid-to-late game weapons including spec and niche weapons. 

* **One-handed weapons**: Abyssal dagger, Abyssal tentacle, Abyssal whip, Blade of saeldor, Dragon battleaxe, Dragon dagger, Dragon hasta, Dragon hunter lance, Dragon longsword, Dragon mace, Dragon scimitar, Dragon sword, Dragon warhammer, Ghrazi rapier, Granite hammer, Granite longsword, Inquisitor's mace, Keris partisan, Leaf-bladed battleaxe, Leaf-bladed sword, Osmumten's khopesh, Sarachnis cudgel, Toktz-xil-ak, Toktz-xil-ek, Tzhaar-ket-em, Viggora's chainmace, Zamorakian hasta, Zombie axe

* **Two-handed weapons**: Abyssal bludgeon, Armadyl godsword, Bandos godsword, Barrelchest anchor, Burning claws, Colossal blade, Crystal halberd, Dharok's greataxe, Dragon 2h sword, Dragon claws, Dragon halberd, Dragon spear, Dual macuahuitl, Elder maul, Granite maul, Guthan's warspear, Leaf-bladed spear, Noxious halberd, Saradomin godsword, Saradomin sword, Sara's blessed sword (full), Scythe of vitur, Soulreaper axe, Torag's hammers, Tzhaar-ket-om, Verac's flail, Zamorak godsword, Zamorakian spear

The second group contains only the best 4-5 weapons of each attack type that you would use as a main weapon to whack the boss, which I refer to as mid-to-late game "meta" weapons. 

* **One-handed "meta" weapons**: Abyssal tentacle, Abyssal whip, Blade of saeldor, Dragon scimitar, Ghrazi rapier, Inquisitor's mace, Osmumten's khopesh, Sarachnis cudgel, Zamorakian hasta, Zombie axe

* **Two-handed "meta" weapons**: Abyssal bludgeon, Dual macuahuitl, Scythe of vitur, Soulreaper axe

Neither set is a perfect representation of weapon distribution, but just take it for what it's worth!
