# Neververse NFT

The Neververse NFT is your passport to the Solnova Universe. It is not just a collectible; it is a productive asset, a piece of digital real estate, and a key to gameplay.

![Star Types Placeholder](placeholder_star_types.png)
*Visual representation of different Star Types and their glows.*

## NFT Types & Rarity

The Neververse is populated by stars of different magnitudes. The rarity of your NFT determines the potential of your Star System.

| NFT Rarity | Probability | Star Type ID |
| :--- | :--- | :--- |
| **Common** | 64% | 12 |
| **Uncommon** | 25% | 8 |
| **Rare** | 10% | 6 |
| **Epic** | 9% | 3 |
| **Legendary** | 1% | 3 |

*   **StarType** defines the rarity and visual characteristics of the NFT.
*   **Visual Components:** The art is generatively created from various components (StarType, CardType, OuterBG, InnerBG).

## NFT Functions & Utility

Owning a Solnova NFT grants you:
1.  **Ownership of a Star System:** You get a Star and a set of Planets orbiting it.
2.  **SNOVA Farming:** Your Star generates SNOVA tokens over time.
3.  **Gameplay Access:** Participate in the ecosystem, customize your planets, and interact with others.
4.  **Brand Interaction (Season 4):** Rent out your planets to brands for rewards.

## Star Properties

Each Star NFT is minted with specific initial parameters that define its gameplay potential.

### 1. Initial Brightness
*   **Range:** 10% - 30% (Random).
*   **Maximum:** 100%.
*   **Effect:** Brightness determines how many planets are visible (unlocked) and affects the SNOVA farming rate.

### 2. Initial Stars
*   The number of already opened planets from the very beginning.
*   **Dependency:** Depends on Initial Brightness (Minimum 1).

### 3. Max Planets
*   The total number of planets that will be opened around this star when Brightness reaches 100%.
*   **Dependency:** Rarity.

| Rarity | Max Planets | Minimum Planets |
| :--- | :--- | :--- |
| Common | Up to 6 | 2 |
| Uncommon | Up to 8 | 4 |
| Rare | Up to 12 | 6 |
| Epic | Up to 16 | 8 |
| Legendary | Up to 24 | 10 |

### 4. Initial Size
*   The physical size of the Star in the Neververse.
*   **Dependency:** Rarity. Legendary stars are significantly larger (up to 2.5x average size) than Common ones.

### 5. Farming Coefficients
*   **Default Farming Capacity:** Base SNOVA generation per hour per planet.
*   **Farming Coefficient:** A multiplier based on Star Rarity.
*   **Planet Farming Coefficient:** A multiplier specific to each planet (Boosted x2 by Satellites).

> [!TIP]
> **Full Brightness Boost:** Reaching 100% brightness gives a **x2 Multiplier** to the Farming Coefficient for the Star and all its planets.

### 6. Coordinate & Color
*   **Color:** Random color from the range corresponding to the NFT Rarity.
*   **Coordinate:** The actual physical address in the Neververse.
    *   **Rule:** Stars are distributed evenly from the center to the periphery.
    *   **Evolution:** Older stars (Genesis) remain closer to the Galaxy Center. New stars from later seasons appear on the expanding borders.

---

## Genesis NFTs (The First 1000)

The first 1000 NFTs minted during the Presale are the **Genesis Collection**. These are the ancient giants of the Neververse, holding special privileges.

### Exclusive Benefits:
1.  **x2 Default Farming Coefficient:** They farm SNOVA twice as fast as standard stars.
2.  **Central Area Position:** Located in the heart of the Neververse Galaxy.
3.  **Unique Visuals:** Distinctive gradient glow.
4.  **10-Year Farming Limit:** While later seasons have reduced farming limits, Genesis Stars can farm SNOVA for **120 months (10 years)**.

![Genesis Star Placeholder](placeholder_genesis_star.png)
*Concept art of a Genesis Star with its unique gradient glow.*

---

## Seasonal Release Structure

The Neververse evolves in Seasons. Each season introduces new NFTs with different economics.

| Season | NFT Supply | Farming Limit (Months) | Full Price (SOL) |
| :--- | :--- | :--- | :--- |
| **Presale (Genesis)** | 1,000 | **120** | - |
| **Season 1 (Big Bang)** | 5,000 | 15 | 2 |
| **Season 2** | 10,000 | 12 | 2.5 |
| **Season 3** | 20,000 | 9 | 3 |
| **Season 4 (Brands)** | 30,000 | 6 | 3.5 |
| **Brands Era** | 55,000 | 0 | 4 |

> [!WARNING]
> **Post-Farming Era:** New NFTs minted in the Post-Farming Era (Season 5+) will **not** have SNOVA farming ability. Their value will be derived entirely from Brand interactions (renting planets for Portals and Satellites for Nuggets).

