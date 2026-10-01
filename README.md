# Úkol 003 - Hoď kostkou (XML a Jetpack Compose)

## Porovnání aktualizace zobrazené kostky (XML vs. Compose)

* **XML verze:** Tady je design v XML souboru. Abych změnil kostku v kódu, musím nejdřív ten textový prvek najít přes `findViewById()`. Až pak mu můžu ručně přiřadit novou hodnotu (např. `tvDice.text = nová_hodnota`). Je to takové víc manuální.
* **Compose verze:** Tady to funguje úplně jinak a vlastně se to mění tak nějak samo. Mám tam jen proměnnou (v mém případě `currentDice`) a jakmile v kódu změním její hodnotu, aplikace sama pozná, že se má obrazovka překreslit. Nemusím tam vůbec nic hledat, prostě se ten nový znak ukáže automaticky.
