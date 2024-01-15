# ScraperAnalysis

## 4D Transfer Matrix Linear Care no Coupling
In this code the beam is generated at the beginning of the AD ring and transfported by means of the 4D transfer matrix at the scraper location.
Here a n-turn maps is implemented to simulate the scraper measurements. Losses are recored as they would occur in the real case and the emittance is reconstructed by means of the Abel Transform as well as by fitting the losses. Comparison between the 2 appraoches provides information on how good the process is.

## Abel Transform Test
This code has been first written to develop, test and check that the ad-hoc Abel Transform could provide results comparable to the Python version. Moreover, the Abel Transform has been enriched with the possibility of performing oversamples. The number of points to be present in a certain region as well as the range for the oversample can be determined by the user.
