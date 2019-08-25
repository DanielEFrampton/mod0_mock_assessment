Class: Plant

Attributes:
plantCommonName (string)
genus (string)
species (string)
adultHeightInInches (float)
currentHeightInInches (float)
numberOfStalks (integer)
plantIsAlive (boolean)

Methods:
killPlant (changes plantIsAlive to false)
growToAdultHeight (changes currentHeightInInches to equal value of adultHeightInInches)
growNewStalk (increments numberOfStalks by 1)
scientificName (returns concatenated strings of genus + species)
