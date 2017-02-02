help()
undo help.request()
help.request()
demo()
help.start
topic
head(df2)
df2 <- read.table("C:/Users/Victoria/Desktop/R-Course-2016/data/03-1_aeh(m).txt", header=TRUE)
df2
table(df2$GESCHLECHT)
barplot(table(df2$GESCHLECHT))
head(df2)
table(df2$GENRE)
install.packages("swirl")
library("swirl")
swirl()
5+7
x <- 5+7
x
x-3
y <- x - 3
y
z <- c(1.1, 9, 3.14)
?c
z
z(555)
q <- (z,555,z)
z <- c(555)
c(z, 555, z)
z * 2 + 100
my_sqrt <- sqrt(z-1)
my_sqrt
my_div <- c(z/my_sqrt)
my_div <- z / my_sqrt
my_div
c(1, 2, 3, 4) + c(0, 10)
c(1, 2, 3, 4) + c(0, 10, 100)
z * 2 + 1000
my_div
swirl()
library("swirl")
ls()
rm(list=ls())
swirl()
data(cars)
?cars
head()
data(cars)
head(cars)
plot(data("cars"))
plot(cars)
?plot()
?plot
plot(x, y)
plot(x= cars$speed, y = cars$dist)
plot(x= cars$dist, y = cars$speed)
plot(x= cars$speed, y = cars$dist)
plot(x = cars$speed, y = cars$dist, xlab = "Speed")
plot(x = cars$speed, y = cars$dist, xlab = "Speed", ylab= "Dist")
plot(x = cars$speed, y = cars$dist, ylab = "Stopping Distance")
plot(x= cars$speed, y = cars$dist)
plot(x = cars$speed, y = cars$dist, xlab = "Speed", ylab = "Stopping Distance")
main("My Plot")
plot(cars, main = "My Plot")
plot(cars, main = "My Plot", submain = "My Plot Subtitle")
plot(cars, sub = "My Plot Subtitle")
plot(cars, col = "2")
plot(cars, col = 2)
plot(cars, col = 2, xlim = c(10, 15))
plot(cars, xlim = c(10, 15))
plot(cars, pch = 2)
?mtcars
ls()
library(swirl)
swirl()
rm(list=ls())
q()
library(readr)
install.packages("tidyverse")
library(tidyverse)
library(tidyverse)
library(readr)
install.packages("tidyverse")
library(tidyverse)
install.packages("readr")
library(readr)
?seq
seq()
seq(1, 100)
plot(rnorm(100))
plot(rnorm(100))
set.seed(1)
plot(rnorm(100))
plot(rnorm(100))
satz <- c("Ich", "gehe", "die", "Schule", ".")
nchar(satz)
attach(df)
attach(df)
attach(df1)
attach(df2)
typeof(df)
class(df)
head(FILLER)
summaey(rnorm(100))
summary(rnorm(100))
summary(LAENGE)
?hist
df <- read.table('../data/t_990505_47.xml', header = T)
library(XML)
tokens <- vector('character')
types <- vector('character')
<<<<<<< HEAD
library(XML)
tokens <- vector('character')
types <- vector('character')
wortart <- vector('character')
genus <- vector('character')
xmlEventParse(
"../data/t_990505_47.xml",
handlers = list(
't' = function(name, attr) {
tokens <<- c(tokens, attr['word'])
types <<- c(types, attr['lemma'])
wortart <<- c(wortart, attr['pos'])
genus <<- c(genus, attr['morph'])
## morphology
}
),
addContext = FALSE
)
#names(tokens) <- NULL
tokens <- unname(tokens)
length <- c(length(tokens))
laenge <- c(nchar(tokens))
laenge
tokens
df3 <- data.frame(tokens, laenge)
df3
table(df3)
sort(table(df3))
hist(table(df3))
barplot(table(df3))
barplot(table(df3))
library(ggplot2)
install.packages(ggplot2)
library("ggplot2", lib.loc="~/R/win-library/3.3")
install.packages('ggplot2')
hist(df3)
detach("package:ggplot2", unload=TRUE)
library("ggplot2", lib.loc="~/R/win-library/3.3")
table(df3$laenge)
hist(table(df3$laenge))
barplot(table(df3$laenge))
geom_bar(table(df3$laenge))
ggplot(table(df3$laenge))
?ggplot2
p <- ggplot(data=df3, aes(x=laenge), y=tokens)) +
geom_bar(stat="identity")
p
p <- ggplot(data=df3, aes(x=laenge), y=tokens)) + geom_bar(stat="identity")
p
p <- ggplot(data=df3, aes(x=laenge, y=tokens)) + geom_bar(stat="identity")
p
summary(df1$types)
df1
summary(types)
cumsum(types)
summary(cumsum(types))
kursA <- rep(1:6, 1:6)
kursB <- rep(seq(1,12,by=2), 1:6)
kursA
kursB
install.packages(moments)
install.packages("moments")
library(moments)
summary(pause.length)
planungspausen <- read.table('../data/03-1_aeh(m).txt', header = T)
summary(pause.length)
install.packages("ggplot2")
ls()
kursA
install.packages("moments")
library(moments)
planungspausen <- read.table('../data/03-1_aeh(m).txt', header = T)
Wikipediaartikel <- read.table('C:/Users/Victoria/Desktop/R-Course-2016/data/R.Köhler.txt')
x <- c(R.Köhler.txt)
x <- c("R.Köhler.txt")
x
Wikipediaartikel <- read.csv('C:/Users/Victoria/Desktop/R-Course-2016/data/R.Köhler.txt')
ls()
planungspausen
Wikipediaartikel <- scan('C:/Users/Victoria/Desktop/R-Course-2016/data/R.Köhler.txt')
Wikipediaartikel <- scan('C:/Users/Victoria/Desktop/R-Course-2016/data/R.Köhler.csv')
install.packages("tm")
install.packages("wordcloud")
install.packages("plotrix")
library(wordcloud)
install.packages("RColorBrewer")
savehistory("C:/Users/Victoria/Desktop/R-Course-2016/Session_08/README.md")
