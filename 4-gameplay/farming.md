# ⚡ SNOVA Farming

The core economic loop is **Farming**. Your Star System generates SNOVA tokens based on its activity and development.

## Logic of Farming
The key component of farming is the **Planet**.
*   **Inactive Planet:** A planet without a GIF. Produces 0 SNOVA.
*   **Active Planet:** A planet with a GIF set. **It is actively farming SNOVA.**

## The Farming Formula
How much SNOVA does a Star generate?

> **MaxStarFarmingCapacity (SNOVA/h) =**
>
> `DefaultCapacity` × `StarFarmingCoeff` × `PlanetFarmingCoeff` × `ActivePlanets` × `BrightnessBoost` × `SatelliteBoost`

**Parameters:**
1.  **DefaultCapacity:** Base generation per planet (e.g., 1 SNOVA/hour).
2.  **StarFarmingCoeff:** Multiplier based on Star Rarity (Random, NFT-given).
3.  **PlanetFarmingCoeff:** Random efficiency coefficient for each planet.
4.  **ActivePlanets:** Number of open planets with GIFs.
5.  **BrightnessBoost:** **x2** when Star reaches 100% Brightness.
6.  **SatelliteBoost:** **x2** for a specific planet when it has 15 satellites orbiting it.

### SNOVA Farming Model

The model below shows how much SNOVA Stars of different rarity generate:

| NFT | Rarity | defaultFarmingCapacity, SNOVA | av. FarmingCoefficient | FullBrightnessBoost | av. PlanetFarmingCoefficient | SatelliteBoost | av. MaxPlanets | av. MaxStarFarmingCapacity, SNOVA /h | av. Generated daily, SNOVA | av. Generated monthly by NFT 1, SNOVA | Price of 100% Brightnes the star (= 3 months of farming) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Common | 60.00% | 0.1 | 1 | 2 | 1.05 | 2 | 4 | 1.7 | 40.3 | 1,250 | 3,750 |
| Uncommon | 24.00% | 0.1 | 1.3 | 2 | 1.15 | 2 | 6 | 3.6 | 86.1 | 2,669 | 8,008 |
| Rare | 10.00% | 0.1 | 1.5 | 2 | 1.25 | 2 | 9 | 6.8 | 162.0 | 5,022 | 15,066 |
| Epic | 5.00% | 0.1 | 1.8 | 2 | 1.35 | 2 | 12 | 11.7 | 279.9 | 8,678 | 26,034 |
| Legendary | 1.00% | 0.1 | 2.25 | 2 | 1.45 | 2 | 17 | 22.2 | 532.4 | 16,506 | 49,517 |

## Farming Impact Factors
*   **NFT-Given Rarity:** Higher rarity = Higher coefficients and more Max Planets.
*   **Strategy:** You can significantly increase yield by **Shining Up** (unlocking planets) and **Socializing** (attracting satellites).

> [!NOTE]
> *Interactive Component: Farming Calculator*
> Imagine a calculator here where you select your NFT Rarity and Current Brightness to see your estimated Daily and Monthly SNOVA production.

---

## 🔥 Burn to Shine

<div style="text-align: center; margin: 3rem 0;">
<img src="../assets/3.png" alt="Burn to Shine Mechanics" style="width: 100%; max-width: 1200px; height: auto;" />
</div>
<p style="text-align: center; color: #999; font-size: 0.9em; margin-top: 0.5rem;">Infographic showing the correlation: Burn SNOVA -> Increase Brightness -> Unlock Planets -> Increase Farming.</p>

To maximize your farming potential, you must upgrade your Star. This process is called **Shining Up**.

### Mechanics
*   **Cost:** You burn SNOVA tokens to increase your Star's Brightness.
*   **Effect:** **1 Boost step = 1 New Orbit (Planet) Opens.**
*   **Visuals:** Orbits start glowing, the Star grows physically larger, and new planets appear.

### The Price of Greatness
The cost to reach 100% Brightness is a constant designed for stability.
> **Price of 100% Brightness =** Equivalent to **3 Months** of Maximum Possible Farming for that specific Star.

*Logic:* You reinvest 3 months of potential earnings to permanently double your output (via the x2 Brightness Boost and unlocking all planets).

### 100% Brightness Privileges
Reaching the maximum brightness is the ultimate goal for a Star Owner:
1.  **All Planets Open:** Maximum farming slots available.
2.  **Full Brightness Boost:** **x2 Multiplier** to SNOVA production.
3.  **GOD Placement:** Ability to place a "GOD" (Huge GIF) on the Star.
4.  **Star Texture:** Ability to customize the Star's texture.
5.  **Brand Eligibility (Season 4):** Your star becomes eligible to host Brand Campaigns and earn extra rewards.
