#include <stdio.h>

int main() {
    int role;
    int stuffrole;
    int running = 1;

    int dailyRevenue = 0;
    int confirm;
    int continueDay = 1;

    int steakMeatCost = 16, potatoCost = 2, vegetableCost = 3;
    int salmonFilletCost = 14, lemonCost = 1, butterCost = 2, riceCost = 2, asparagusCost = 4;
    int chickenBreastCost = 10, herbSauceCost = 2;
    int shrimpCost = 13, garlicCost = 1;
    int pastaCost = 4, mushroomCost = 4, parmesanCost = 3, creamCost = 3;
    int gingerSauceCost = 2, noodlesCost = 3;
    int whiteFishFilletCost = 12, herbsCost = 2, greenBeansCost = 3;
    int beefMeatCost = 15, carrotCost = 2, gravyCost = 2;
    int beefPattyCost = 9, cheeseCost = 2, lettuceCost = 1, tomatoCost = 2, friesCost = 3;
    int mozzarellaCost = 5, basilCost = 1;

    int grilledSteakPrice = 42, panSearedSalmonPrice = 35, roastChickenPrice = 30;
    int garlicButterShrimpPrice = 33, creamyMushroomPastaPrice = 26, vegetableStirFryPrice = 23;
    int bakedWhiteFishPrice = 31, beefPotRoastPrice = 37, classicCheeseburgerPrice = 22, margheritaPizzaPrice = 24;

    int steakQuantity = 7, potatoQuantity = 18, vegetableQuantity = 16;
    int salmonQuantity = 14, lemonQuantity = 20, butterQuantity = 15, riceQuantity = 18, asparagusQuantity = 12;
    int chickenQuantity = 8, herbSauceQuantity = 12;
    int shrimpQuantity = 14, garlicQuantity = 16;
    int pastaQuantity = 17, mushroomQuantity = 7, parmesanQuantity = 12, creamQuantity = 14;
    int gingerSauceQuantity = 12, noodlesQuantity = 16;
    int whiteFishQuantity = 13, herbsQuantity = 15, greenBeansQuantity = 12;
    int beefQuantity = 14, carrotQuantity = 17, gravyQuantity = 12;
    int beefPattyQuantity = 15, cheeseQuantity = 18, lettuceQuantity = 16, tomatoQuantity = 17, friesQuantity = 15;
    int mozzarellaQuantity = 14, basilQuantity = 12;

    while (running == 1) {
        printf("\n\n\n\n\n");
        printf("  +----------------------------------+\n");
        printf("  |        TALTECH RESTAURANT        |\n");
        printf("  +----------------------------------+\n");
        printf("    [1] Client Portal                \n");
        printf("    [2] Staff Management             \n");
        printf("    [3] Exit System                  \n");
        printf("\n\n\n\nChoose an option:\n> ");
        scanf("%d", &role);

        switch (role) {
            case 1: {
                int reservation, availableTable = 2, foodChoice;

                printf("\n\n\n\n\n\n\n\n\n");
                printf("  +----------------------------------+\n");
                printf("  |        CLIENT RESERVATION        |\n");
                printf("  +----------------------------------+\n");
                printf("  Does the client have a reservation?\n");
                printf("    [1] Yes                          \n");
                printf("    [2] No                           \n");
                printf("\n\n\n\nChoose an option:\n> ");
                scanf("%d", &reservation);

                if (reservation != 1) {
                    printf("\n\n\n\n\n\n\n\n\n");
                    printf("  +----------------------------------+\n");
                    printf("  |        TABLE AVAILABILITY        |\n");
                    printf("  +----------------------------------+\n");
                    printf("  Is a table available right now?    \n");
                    printf("    [1] Yes                          \n");
                    printf("    [2] No                           \n");
                    printf("\n\n\n\nChoose an option:\n> ");
                    scanf("%d", &availableTable);
                }

                if (reservation != 1 && availableTable != 1) {
                    printf("\n  [!] Notice: No table is available at the moment. Returning to main menu...\n");
                    break;
                }

                printf("\n  * Success: The client is seated.\n");
                printf("  * The waiter presents the culinary menu.\n\n");

                printf("  +----------------------------------------------------------------------+\n");
                printf("  |                              FOOD MENU                               |\n");
                printf("  +----------------------------------------------------------------------+\n");
                printf("  [1] Grilled Steak     - 42 EUR  |  [6] Vegetable Stir-Fry- 23 EUR    \n");
                printf("      (Mashed potatoes)           |      (Veggies & noodles)             \n\n");
                printf("  [2] Pan-Seared Salmon - 35 EUR  |  [7] Baked White Fish  - 31 EUR    \n");
                printf("      (Lemon butter & rice)       |      (Lemon, herbs & beans)          \n\n");
                printf("  [3] Roast Chicken     - 30 EUR  |  [8] Beef Pot Roast    - 37 EUR    \n");
                printf("      (Carrots & gravy)           |      (Carrots & gravy)               \n\n");
                printf("  [4] Garlic Shrimp     - 33 EUR  |  [9] Cheeseburger      - 22 EUR    \n");
                printf("      (Garlic butter & rice)      |      (Cheese, tomato & fries)        \n\n");
                printf("  [5] Mushroom Pasta    - 26 EUR  |  [10] Margherita Pizza - 24 EUR    \n");
                printf("      (Parmesan & cream)          |      (Mozzarella & basil)            \n");
                printf("  +----------------------------------------------------------------------+\n");
                printf("Choose a dish [1-10]:\n> ");
                scanf("%d", &foodChoice);

                printf("\n  > Waiter writes [");
                switch (foodChoice) {
                    case 1: printf("Grilled Steak"); break;
                    case 2: printf("Pan-Seared Salmon"); break;
                    case 3: printf("Roast Chicken"); break;
                    case 4: printf("Garlic Butter Shrimp"); break;
                    case 5: printf("Creamy Mushroom Pasta"); break;
                    case 6: printf("Vegetable Stir-Fry"); break;
                    case 7: printf("Baked White Fish"); break;
                    case 8: printf("Beef Pot Roast"); break;
                    case 9: printf("Classic Cheeseburger"); break;
                    case 10: printf("Margherita Pizza"); break;
                    default: printf("Unknown Dish"); break;
                }
                printf("] on order slip.\n");

                printf("\n  > Order transmitted to the kitchen chef.\n");
                printf("  [Press 1 to run Ingredient Inventory Check]:\n> ");
                scanf("%d", &confirm);

                printf("\n  [Ingredient Inventory Check Status]\n");

                int totalCost = 0;
                int dishPrice = 0;
                int serviceFee = 0;
                int totalPaid = 0;

                if (foodChoice == 1) { dishPrice = 42; serviceFee = 4; totalPaid = 46; }
                else if (foodChoice == 2) { dishPrice = 35; serviceFee = 4; totalPaid = 39; }
                else if (foodChoice == 3) { dishPrice = 30; serviceFee = 3; totalPaid = 33; }
                else if (foodChoice == 4) { dishPrice = 33; serviceFee = 3; totalPaid = 36; }
                else if (foodChoice == 5) { dishPrice = 26; serviceFee = 3; totalPaid = 29; }
                else if (foodChoice == 6) { dishPrice = 23; serviceFee = 2; totalPaid = 25; }
                else if (foodChoice == 7) { dishPrice = 31; serviceFee = 3; totalPaid = 34; }
                else if (foodChoice == 8) { dishPrice = 37; serviceFee = 4; totalPaid = 41; }
                else if (foodChoice == 9) { dishPrice = 22; serviceFee = 2; totalPaid = 24; }
                else if (foodChoice == 10) { dishPrice = 24; serviceFee = 2; totalPaid = 26; }

                int hasIngredients = 1;
                if (foodChoice == 1 && (steakQuantity < 10 || potatoQuantity < 10 || vegetableQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 2 && (salmonQuantity < 10 || lemonQuantity < 10 || butterQuantity < 10 || riceQuantity < 10 || asparagusQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 3 && (chickenQuantity < 10 || herbSauceQuantity < 10 || potatoQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 4 && (shrimpQuantity < 10 || garlicQuantity < 10 || butterQuantity < 10 || riceQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 5 && (pastaQuantity < 10 || mushroomQuantity < 10 || parmesanQuantity < 10 || creamQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 6 && (vegetableQuantity < 10 || gingerSauceQuantity < 10 || noodlesQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 7 && (whiteFishQuantity < 10 || lemonQuantity < 10 || herbsQuantity < 10 || greenBeansQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 8 && (beefQuantity < 10 || carrotQuantity < 10 || potatoQuantity < 10 || gravyQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 9 && (beefPattyQuantity < 10 || cheeseQuantity < 10 || lettuceQuantity < 10 || tomatoQuantity < 10 || friesQuantity < 10)) hasIngredients = 0;
                if (foodChoice == 10 && (mozzarellaQuantity < 10 || tomatoQuantity < 10 || basilQuantity < 10)) hasIngredients = 0;

                switch (foodChoice) {
                    case 1:
                        if (steakQuantity >= 10) { printf("  - Steak Meat   [v] %d/10\n", steakQuantity); } else { printf("  - Steak Meat   [!] %d/10\n", steakQuantity); }
                        if (potatoQuantity >= 10) { printf("  - Potatoes     [v] %d/10\n", potatoQuantity); } else { printf("  - Potatoes     [!] %d/10\n", potatoQuantity); }
                        if (vegetableQuantity >= 10) { printf("  - Vegetables   [v] %d/10\n", vegetableQuantity); } else { printf("  - Vegetables   [!] %d/10\n", vegetableQuantity); }
                        break;
                    case 2:
                        if (salmonQuantity >= 10) { printf("  - Salmon Fillet [v] %d/10\n", salmonQuantity); } else { printf("  - Salmon Fillet [!] %d/10\n", salmonQuantity); }
                        if (lemonQuantity >= 10) { printf("  - Lemon         [v] %d/10\n", lemonQuantity); } else { printf("  - Lemon         [!] %d/10\n", lemonQuantity); }
                        if (butterQuantity >= 10) { printf("  - Butter        [v] %d/10\n", butterQuantity); } else { printf("  - Butter        [!] %d/10\n", butterQuantity); }
                        if (riceQuantity >= 10) { printf("  - Rice          [v] %d/10\n", riceQuantity); } else { printf("  - Rice          [!] %d/10\n", riceQuantity); }
                        if (asparagusQuantity >= 10) { printf("  - Asparagus     [v] %d/10\n", asparagusQuantity); } else { printf("  - Asparagus     [!] %d/10\n", asparagusQuantity); }
                        break;
                    case 3:
                        if (chickenQuantity >= 10) { printf("  - Chicken Breast [v] %d/10\n", chickenQuantity); } else { printf("  - Chicken Breast [!] %d/10\n", chickenQuantity); }
                        if (herbSauceQuantity >= 10) { printf("  - Herb Sauce     [v] %d/10\n", herbSauceQuantity); } else { printf("  - Herb Sauce     [!] %d/10\n", herbSauceQuantity); }
                        if (potatoQuantity >= 10) { printf("  - Potatoes       [v] %d/10\n", potatoQuantity); } else { printf("  - Potatoes       [!] %d/10\n", potatoQuantity); }
                        break;
                    case 4:
                        if (shrimpQuantity >= 10) { printf("  - Shrimp [v] %d/10\n", shrimpQuantity); } else { printf("  - Shrimp [!] %d/10\n", shrimpQuantity); }
                        if (garlicQuantity >= 10) { printf("  - Garlic [v] %d/10\n", garlicQuantity); } else { printf("  - Garlic [!] %d/10\n", garlicQuantity); }
                        if (butterQuantity >= 10) { printf("  - Butter [v] %d/10\n", butterQuantity); } else { printf("  - Butter [!] %d/10\n", butterQuantity); }
                        if (riceQuantity >= 10) { printf("  - Rice   [v] %d/10\n", riceQuantity); } else { printf("  - Rice   [!] %d/10\n", riceQuantity); }
                        break;
                    case 5:
                        if (pastaQuantity >= 10) { printf("  - Pasta    [v] %d/10\n", pastaQuantity); } else { printf("  - Pasta    [!] %d/10\n", pastaQuantity); }
                        if (mushroomQuantity >= 10) { printf("  - Mushroom [v] %d/10\n", mushroomQuantity); } else { printf("  - Mushroom [!] %d/10\n", mushroomQuantity); }
                        if (parmesanQuantity >= 10) { printf("  - Parmesan [v] %d/10\n", parmesanQuantity); } else { printf("  - Parmesan [!] %d/10\n", parmesanQuantity); }
                        if (creamQuantity >= 10) { printf("  - Cream    [v] %d/10\n", creamQuantity); } else { printf("  - Cream    [!] %d/10\n", creamQuantity); }
                        break;
                    case 6:
                        if (vegetableQuantity >= 10) { printf("  - Vegetables  [v] %d/10\n", vegetableQuantity); } else { printf("  - Vegetables  [!] %d/10\n", vegetableQuantity); }
                        if (gingerSauceQuantity >= 10) { printf("  - GingerSauce [v] %d/10\n", gingerSauceQuantity); } else { printf("  - GingerSauce [!] %d/10\n", gingerSauceQuantity); }
                        if (noodlesQuantity >= 10) { printf("  - Noodles     [v] %d/10\n", noodlesQuantity); } else { printf("  - Noodles     [!] %d/10\n", noodlesQuantity); }
                        break;
                    case 7:
                        if (whiteFishQuantity >= 10) { printf("  - White Fish [v] %d/10\n", whiteFishQuantity); } else { printf("  - White Fish [!] %d/10\n", whiteFishQuantity); }
                        if (lemonQuantity >= 10) { printf("  - Lemon      [v] %d/10\n", lemonQuantity); } else { printf("  - Lemon      [!] %d/10\n", lemonQuantity); }
                        if (herbsQuantity >= 10) { printf("  - Herbs      [v] %d/10\n", herbsQuantity); } else { printf("  - Herbs      [!] %d/10\n", herbsQuantity); }
                        if (greenBeansQuantity >= 10) { printf("  - GreenBeans [v] %d/10\n", greenBeansQuantity); } else { printf("  - GreenBeans [!] %d/10\n", greenBeansQuantity); }
                        break;
                    case 8:
                        if (beefQuantity >= 10) { printf("  - Beef    [v] %d/10\n", beefQuantity); } else { printf("  - Beef    [!] %d/10\n", beefQuantity); }
                        if (carrotQuantity >= 10) { printf("  - Carrots [v] %d/10\n", carrotQuantity); } else { printf("  - Carrots [!] %d/10\n", carrotQuantity); }
                        if (potatoQuantity >= 10) { printf("  - Potatoes[v] %d/10\n", potatoQuantity); } else { printf("  - Potatoes[!] %d/10\n", potatoQuantity); }
                        if (gravyQuantity >= 10) { printf("  - Gravy   [v] %d/10\n", gravyQuantity); } else { printf("  - Gravy   [!] %d/10\n", gravyQuantity); }
                        break;
                    case 9:
                        if (beefPattyQuantity >= 10) { printf("  - Beef Patty [v] %d/10\n", beefPattyQuantity); } else { printf("  - Beef Patty [!] %d/10\n", beefPattyQuantity); }
                        if (cheeseQuantity >= 10) { printf("  - Cheese     [v] %d/10\n", cheeseQuantity); } else { printf("  - Cheese     [!] %d/10\n", cheeseQuantity); }
                        if (lettuceQuantity >= 10) { printf("  - Lettuce    [v] %d/10\n", lettuceQuantity); } else { printf("  - Lettuce    [!] %d/10\n", lettuceQuantity); }
                        if (tomatoQuantity >= 10) { printf("  - Tomato     [v] %d/10\n", tomatoQuantity); } else { printf("  - Tomato     [!] %d/10\n", tomatoQuantity); }
                        if (friesQuantity >= 10) { printf("  - Fries      [v] %d/10\n", friesQuantity); } else { printf("  - Fries      [!] %d/10\n", friesQuantity); }
                        break;
                    case 10:
                        if (mozzarellaQuantity >= 10) { printf("  - Mozzarella [v] %d/10\n", mozzarellaQuantity); } else { printf("  - Mozzarella [!] %d/10\n", mozzarellaQuantity); }
                        if (tomatoQuantity >= 10) { printf("  - Tomatoes   [v] %d/10\n", tomatoQuantity); } else { printf("  - Tomatoes   [!] %d/10\n", tomatoQuantity); }
                        if (basilQuantity >= 10) { printf("  - Basil      [v] %d/10\n", basilQuantity); } else { printf("  - Basil      [!] %d/10\n", basilQuantity); }
                        break;
                }

                if (hasIngredients == 0) {
                    printf("\n  [!] Missing ingredients detected!\n");
                    if (foodChoice == 1) {
                        if (steakQuantity < 10) totalCost += (15 - steakQuantity) * steakMeatCost;
                        if (potatoQuantity < 10) totalCost += (15 - potatoQuantity) * potatoCost;
                        if (vegetableQuantity < 10) totalCost += (15 - vegetableQuantity) * vegetableCost;
                    } else if (foodChoice == 2) {
                        if (salmonQuantity < 10) totalCost += (15 - salmonQuantity) * salmonFilletCost;
                        if (lemonQuantity < 10) totalCost += (15 - lemonQuantity) * lemonCost;
                        if (butterQuantity < 10) totalCost += (15 - butterQuantity) * butterCost;
                        if (riceQuantity < 10) totalCost += (15 - riceQuantity) * riceCost;
                        if (asparagusQuantity < 10) totalCost += (15 - asparagusQuantity) * asparagusCost;
                    } else if (foodChoice == 3) {
                        if (chickenQuantity < 10) totalCost += (15 - chickenQuantity) * chickenBreastCost;
                        if (herbSauceQuantity < 10) totalCost += (15 - herbSauceQuantity) * herbSauceCost;
                        if (potatoQuantity < 10) totalCost += (15 - potatoQuantity) * potatoCost;
                    } else if (foodChoice == 4) {
                        if (shrimpQuantity < 10) totalCost += (15 - shrimpQuantity) * shrimpCost;
                        if (garlicQuantity < 10) totalCost += (15 - garlicQuantity) * garlicCost;
                        if (butterQuantity < 10) totalCost += (15 - butterQuantity) * butterCost;
                        if (riceQuantity < 10) totalCost += (15 - riceQuantity) * riceCost;
                    } else if (foodChoice == 5) {
                        if (pastaQuantity < 10) totalCost += (15 - pastaQuantity) * pastaCost;
                        if (mushroomQuantity < 10) totalCost += (15 - mushroomQuantity) * mushroomCost;
                        if (parmesanQuantity < 10) totalCost += (15 - parmesanQuantity) * parmesanCost;
                        if (creamQuantity < 10) totalCost += (15 - creamQuantity) * creamCost;
                    } else if (foodChoice == 6) {
                        if (vegetableQuantity < 10) totalCost += (15 - vegetableQuantity) * vegetableCost;
                        if (gingerSauceQuantity < 10) totalCost += (15 - gingerSauceQuantity) * gingerSauceCost;
                        if (noodlesQuantity < 10) totalCost += (15 - noodlesQuantity) * noodlesCost;
                    } else if (foodChoice == 7) {
                        if (whiteFishQuantity < 10) totalCost += (15 - whiteFishQuantity) * whiteFishFilletCost;
                        if (lemonQuantity < 10) totalCost += (15 - lemonQuantity) * lemonCost;
                        if (herbsQuantity < 10) totalCost += (15 - herbsQuantity) * herbsCost;
                        if (greenBeansQuantity < 10) totalCost += (15 - greenBeansQuantity) * greenBeansCost;
                    } else if (foodChoice == 8) {
                        if (beefQuantity < 10) totalCost += (15 - beefQuantity) * beefMeatCost;
                        if (carrotQuantity < 10) totalCost += (15 - carrotQuantity) * carrotCost;
                        if (potatoQuantity < 10) totalCost += (15 - potatoQuantity) * potatoCost;
                        if (gravyQuantity < 10) totalCost += (15 - gravyQuantity) * gravyCost;
                    } else if (foodChoice == 9) {
                        if (beefPattyQuantity < 10) totalCost += (15 - beefPattyQuantity) * beefPattyCost;
                        if (cheeseQuantity < 10) totalCost += (15 - cheeseQuantity) * cheeseCost;
                        if (lettuceQuantity < 10) totalCost += (15 - lettuceQuantity) * lettuceCost;
                        if (tomatoQuantity < 10) totalCost += (15 - tomatoQuantity) * tomatoCost;
                        if (friesQuantity < 10) totalCost += (15 - friesQuantity) * friesCost;
                    } else if (foodChoice == 10) {
                        if (mozzarellaQuantity < 10) totalCost += (15 - mozzarellaQuantity) * mozzarellaCost;
                        if (tomatoQuantity < 10) totalCost += (15 - tomatoQuantity) * tomatoCost;
                        if (basilQuantity < 10) totalCost += (15 - basilQuantity) * basilCost;
                    }

                    printf("  > Administrator calculated supplier cost: %d EUR\n", totalCost);
                    printf("  [Press 1 to confirm paying the supplier]:\n> ");
                    scanf("%d", &confirm);
                    printf("  > Administrator pays supplier: %d EUR\n", totalCost);

                    dailyRevenue -= totalCost;

                    if (foodChoice == 1) {
                        if (steakQuantity < 10) steakQuantity = 15;
                        if (potatoQuantity < 10) potatoQuantity = 15;
                        if (vegetableQuantity < 10) vegetableQuantity = 15;
                    }
                    else if (foodChoice == 2) {
                        if (salmonQuantity < 10) salmonQuantity = 15;
                        if (lemonQuantity < 10) lemonQuantity = 15;
                        if (butterQuantity < 10) butterQuantity = 15;
                        if (riceQuantity < 10) riceQuantity = 15;
                        if (asparagusQuantity < 10) asparagusQuantity = 15;
                    }
                    else if (foodChoice == 3) {
                        if (chickenQuantity < 10) chickenQuantity = 15;
                        if (herbSauceQuantity < 10) herbSauceQuantity = 15;
                        if (potatoQuantity < 10) potatoQuantity = 15;
                    }
                    else if (foodChoice == 4) {
                        if (shrimpQuantity < 10) shrimpQuantity = 15;
                        if (garlicQuantity < 10) garlicQuantity = 15;
                        if (butterQuantity < 10) butterQuantity = 15;
                        if (riceQuantity < 10) riceQuantity = 15;
                    }
                    else if (foodChoice == 5) {
                        if (pastaQuantity < 10) pastaQuantity = 15;
                        if (mushroomQuantity < 10) mushroomQuantity = 15;
                        if (parmesanQuantity < 10) parmesanQuantity = 15;
                        if (creamQuantity < 10) creamQuantity = 15;
                    }
                    else if (foodChoice == 6) {
                        if (vegetableQuantity < 10) vegetableQuantity = 15;
                        if (gingerSauceQuantity < 10) gingerSauceQuantity = 15;
                        if (noodlesQuantity < 10) noodlesQuantity = 15;
                    }
                    else if (foodChoice == 7) {
                        if (whiteFishQuantity < 10) whiteFishQuantity = 15;
                        if (lemonQuantity < 10) lemonQuantity = 15;
                        if (herbsQuantity < 10) herbsQuantity = 15;
                        if (greenBeansQuantity < 10) greenBeansQuantity = 15;
                    }
                    else if (foodChoice == 8) {
                        if (beefQuantity < 10) beefQuantity = 15;
                        if (carrotQuantity < 10) carrotQuantity = 15;
                        if (potatoQuantity < 10) potatoQuantity = 15;
                        if (gravyQuantity < 10) gravyQuantity = 15;
                    }
                    else if (foodChoice == 9) {
                        if (beefPattyQuantity < 10) beefPattyQuantity = 15;
                        if (cheeseQuantity < 10) cheeseQuantity = 15;
                        if (lettuceQuantity < 10) lettuceQuantity = 15;
                        if (tomatoQuantity < 10) tomatoQuantity = 15;
                        if (friesQuantity < 10) friesQuantity = 15;
                    }
                    else if (foodChoice == 10) {
                        if (mozzarellaQuantity < 10) mozzarellaQuantity = 15;
                        if (tomatoQuantity < 10) tomatoQuantity = 15;
                        if (basilQuantity < 10) basilQuantity = 15;
                    }
                }

                if (foodChoice == 1) { steakQuantity--; potatoQuantity--; vegetableQuantity--; }
                else if (foodChoice == 2) { salmonQuantity--; lemonQuantity--; butterQuantity--; riceQuantity--; asparagusQuantity--; }
                else if (foodChoice == 3) { chickenQuantity--; herbSauceQuantity--; potatoQuantity--; }
                else if (foodChoice == 4) { shrimpQuantity--; garlicQuantity--; butterQuantity--; riceQuantity--; }
                else if (foodChoice == 5) { pastaQuantity--; mushroomQuantity--; parmesanQuantity--; creamQuantity--; }
                else if (foodChoice == 6) { vegetableQuantity--; gingerSauceQuantity--; noodlesQuantity--; }
                else if (foodChoice == 7) { whiteFishQuantity--; lemonQuantity--; herbsQuantity--; greenBeansQuantity--; }
                else if (foodChoice == 8) { beefQuantity--; carrotQuantity--; potatoQuantity--; gravyQuantity--; }
                else if (foodChoice == 9) { beefPattyQuantity--; cheeseQuantity--; lettuceQuantity--; tomatoQuantity--; friesQuantity--; }
                else if (foodChoice == 10) { mozzarellaQuantity--; tomatoQuantity--; basilQuantity--; }

                printf("\n  [Press 1 to confirm cooking & serving]:\n> ");
                scanf("%d", &confirm);
                printf("  * Chef starts cooking...\n");
                printf("  * Food is ready! Waiter brings the food to the table.\n");

                printf("  +---------------------------------------------------+\n");
                printf("  |                   BILL & PAYMENT                  |\n");
                printf("  +---------------------------------------------------+\n");
                printf("  | Dish Price:  %2d EUR                              |\n", dishPrice);
                printf("  | Service Fee:  %1d EUR                              |\n", serviceFee);
                printf("  | TOTAL PAID:  %2d EUR                              |\n", totalPaid);
                printf("  +---------------------------------------------------+\n");

                printf("  [Press 1 to confirm payment]:\n> ");
                scanf("%d", &confirm);

                dailyRevenue += totalPaid;
                printf("\n  * Current Daily Revenue: %d EUR\n", dailyRevenue);

                printf("\n  Do you want to continue to the next client?\n");
                printf("    [1] Yes\n");
                printf("    [2] No (End Day)\n");
                printf("Choose an option:\n> ");
                scanf("%d", &continueDay);

                if (continueDay != 1) {
                    running = 0;
                }
                break;
            }

            case 2: {
                int passwordanswer;
                printf("\nEnter the Staff PIN:\n> ");
                scanf("%d", &passwordanswer);

                if (passwordanswer == 1918) {
                    printf("\n\n\n\n\n\n\n\n\n");
                    printf("  +----------------------------------+\n");
                    printf("  |           STAFF SYSTEM           |\n");
                    printf("  +----------------------------------+\n");
                    printf("  Status: Coming Soon..\n");
                    printf("    [1] Back to Main Menu            \n");
                    printf("\n\n\n\nChoose an option:\n> ");
                    scanf("%d", &stuffrole);
                    switch (stuffrole) {
                        case 1:
                            printf("\n  > Returning to Main Menu...\n");
                            break;
                        default:
                            printf("\n  [Error] Invalid option! Enter 1.\n");
                            break;
                    }
                }
                else {
                    printf("\n  [Error] Incorrect Password Access Denied!\n");
                }
                break;
            }

            case 3:
                printf("\n  Exiting program. Goodbye!\n");
                running = 0;
                break;

            default:
                printf("\n  [Error] Invalid option! Please enter 1, 2, or 3.\n");
                break;
        }

    }

    printf("\n  * Day Ended. Final Total Revenue: %d EUR. Goodbye!\n", dailyRevenue);
    return 0;
}
