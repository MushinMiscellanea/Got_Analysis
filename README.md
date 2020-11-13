# Sentiment Analysis on Game of Thrones Dialogue

My final project for LIS 4761 Data Mining. I used NLTK abstracted through Orange (python under the hood) to generate sentiment scores for each line of dialogue for the popular T.V. show Game of Thrones. I filtered the results to include only the characters with widepread political appeal. My results map the political climate and overall popularity of each character throughout the shows 8 seasons, approximatly 7 years total.

#### This code is terribly undocumented as it served its purpose of being an A project and nothing more. Proceed with Caution.

## Start

The analysis was done in a third party software called Orange Data Mining. Orange abstracts the already abstracted Python NLTK package for easy, easy use. The software could not perform on all of my filtering needs, so injected python scripts was an easy work around.
The visualization was done in Jupyter Notebook using matplotlib and seaborn.

### Installations


```
brew install python  

pip install jupyter pandas matplotlib numpy seaborn

```

### Installing

Setup a virtual env: My preference is Pipenv
```
pip install pipenv

pipenv install jupyter pandas matplotlib numpy seaborn
```

![rundown gif](/GoTAnalysis/img/workflow.gif)


## Contributing

Thanks Suzanne Raybuck for working through this with me.


## Authors

* **Spencer Finkel** - *Initial work* - [mushinMiscellanea](https://github.com/mushinMiscellanea)



## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Some of the visualization code was pulled from an article by Gref Rafferty 


