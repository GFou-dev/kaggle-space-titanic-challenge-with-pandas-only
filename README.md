# Spaceship Titanic 

## Overview
Exploratory data analysis and prediction for the 
[Spaceship Titanic Kaggle competition](https://www.kaggle.com/competitions/spaceship-titanic), 
only using pandas.

## Approach
The goal of this notebook was to familirize with pandas and data analysis, 
as well as trying to build a small prediction tree based on my findings, 
without the use of Sci-kit learn or any other library.

## Key Findings
- CryoSleep is the number 1 Transportation factor
- Luxury spending (Spa, VRDeck, RoomService) strongly predicts non-transport
- FoodCourt and ShoppingMall spending goes in the opposite direction
- Deck and Homeplanet are very strong transportation indicators
- Passengers decks are divided by HomePlanet
- Ship side is a consistent Transporation % chances increase across all decks
- Young children are a different, independent signal

## Tools used
- Python
- pandas

## Next Steps
- Learn to use ski-kit learn and use it for better prediction

- ## Project Structure

```
space_titanic/
├── space_titanic.ipynb   # Main notebook
└── README.md             # This file
```

---

## License

This project is released under the MIT License.
