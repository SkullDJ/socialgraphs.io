
## Sentiment

Another way of analyzing whether movies have changed over time is with the use of sentiment scores. With sentiment scores it is possible to determine how positive a text is. This is useful in this context as the sentiment scores are able to tell whether movies have become more positive or negative over time or if the happiness has changed at all.   

The sentiment scores were found using the LabMIT 1.0 wordlist which contains 10,222 unique words. The words in this list were found by compiling word lists from four different sources: Twitter, Google Books (English), music lyrics (1960 to 2007), and the New York Times (1987 to 2007). The happiness rating of the individual words were found using Amazon's Mechanical Turk, which evaluates each word by having 50 independent users rate it on a scale of 1 to 9 based on how happy it made them feel. 1 being sad and 9 being happy. The happiness rating of a word is then the average of these 50 ratings. [[1]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0026752)

The average sentiment score for old and new movies for each genre can be seen in the table below. The average sentiment scores for each genre show that new movies generally are more happy than older movies, though only by a very small amount. Since there is no significant change, the reason for the very small increase may be that the summaries were gathered from different sources, and the way of writing the summaries therefore is different.

| **Genre** | **Old** | **New** |
| Drama | 3.99661822315808 | 4.2694862804145846 |
| Comedy | 4.015428685827687 | 4.270641906604659 |
| Fantasy | 3.8763600676484717 | 4.193858546237824 |
| Horror | 3.928773699126107 | 4.1797907367252325 |
| Thriller | 3.869478840420811 | 4.1643483672529715 |
| Adventure | 3.8041229961946006 | 4.22508317139532 |
| Animation | 3.859005224991769 | 4.204639380919053 |
| Documentary | 4.0591986870986965 | 4.27575875759692 |
| History | 3.8266818335940918 | 4.204754225055987 |
| Action | 3.750338174944933 | 4.055393948852797 |
| Biography | 4.045900117821441 | 4.261190579750241 |
| Crime | 3.8489044585987324 | 4.103033597094379 |
| Mystery | 3.9050377524132314 | 4.223669058397805 |
| Music | 4.018652384423135 | 4.392692855755019 |
| Musical | 3.9925137315680375 | 4.352340476880043 |
| Western | 3.8166423126657016 | 4.093394875659371 |
| News | 4.053335552596539 | 4.323256752859757 |

Before computing the sentiment scores it was expected that different genres would have different sentiment scores based on the content of the movies in a particular genre. For example if a movie is violent, its plot might include words which support this and thus be more negative. As seen in the table above this is not the case. The reason they are all basically the same could be because of the neutral language used for writing plot summaries. A score of 5 is neutral, 1 is negative and 9 is positive. Therefore the plot summaries are actually all slightly negative. The reason for the slightly negative scores might be because of the structure of movies, where there is some conflict in the beginning of the story and then this conflict will be resolved at the end. The change from old to new movies are very small ranging from around 0.2 to 0.4 and the reason for this insignificant change is probably also due to the neutral language remaining very neutral. An interesting alternative to sentiment analysis could revolve around the anlysis of movie scripts, opposed to summaries, as this could give a more thorough depiction of the mood of a movie. 



[Next page: Network](network.md)
