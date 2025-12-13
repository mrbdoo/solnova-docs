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

## Farming Impact Factors
*   **NFT-Given Rarity:** Higher rarity = Higher coefficients and more Max Planets.
*   **Strategy:** You can significantly increase yield by **Shining Up** (unlocking planets) and **Socializing** (attracting satellites).

[Interactive Component: Farming Calculator]
> [!NOTE]
> *Imagine a calculator here where you select your NFT Rarity and Current Brightness to see your estimated Daily and Monthly SNOVA production.*

