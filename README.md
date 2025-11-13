# Superhero Movie Analysis: Overview and Objective
This projects takes a dataset of information on superhero movies from various cinematic universes, including Marvel, DC, and others, and answers looks for certain relationships and trends within. For example:
### 1) **Have superhero movies released by major distributors earned significantly more worldwide box office revenue than those from smaller distributors?**
### 2) **Has the average worldwide box office revenue of superhero movies increased over the years?**
### 3) **Do movies based on existing IPs (e.g., comics, TV shows) outperform original superhero movies in worldwide box office revenue?**
### 4) **Do movie sequels/reboots and remakes tend to out-perform their original counterparts?**

## Key insights (Summary)
> For full results, visualisations, and detailed discussion, open the Jupyter notebook Superhero-Movies.ipynb in this repository.
- Cleaned messy columns, and dropped unneccessary and created useful columns, using ```pandas```.
- Visualised distributions (**Box plots**) and trends over time (**Line graphs**) of movie rating and box office revenue by generating plots using```matplotlib``` and ```seaborn```.
- Ran two-sample t-tests to test whether the mean box office revenue between major and independent distributors, as well as between original movies and existing IPs, is significantly different.
  
## Tools and Libraries
| Purpose | Libraries Used |
|----------|----------------|
| Data manipulation | `pandas`, `re` |
| Data visualization | `matplotlib`, `seaborn`, `math` |
| Statistical testing | `scipy.stats (ttest_ind)` |

## Installation
1. **Clone this repository**
   ```bash
   git clone https://github.com/lloydy-92/Superhero-Movies.git
   cd Superhero-Movies
2. **(Optional) Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate       # On Windows use: venv\Scripts\activate
3. **Install dependencies**
   ```bash
   pip install pandas matplotlib seaborn scipy jupyter
4. **Launch the notebook**
   ```bash
   jupyter notebook Superhero-Movies.ipynb

## Project Structure
```bash
Superhero-Movies/
├── Superhero-Movies.ipynb        # Main analysis notebook
├── superhero_movies_dataset.csv  # Dataset of superhero movies information
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## Contributing
Contributions, suggestions, and improvements are welcome and encouraged! If you would like the enhance any aspect of the project, such as analysis or visualisations:
1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/improve-analysis
3. Commit your changes
   ```bash
   git commit -m 'Add new visualisation'
4. Push to the branch
   ```bash
   git push origin feature/improve-analysis
5. Open a Pull Request

## Author
**Sam Lloyd**, sammy.lloyd@live.com, *github.com/lloydy-92*

## Acknowledgements
- Alberto Lawant on Kaggle for providing the dataset (*https://www.kaggle.com/datasets/aslawant/superhero-movies-dataset*)
- Codecademy Data Science Path for providing structured guidance on this project.
- The open-source community for libraries like ```pandas```, ```matplotlib```, and ```seaborn```.
