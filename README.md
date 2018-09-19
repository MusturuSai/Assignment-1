### Which Function

    X<-c(2,4,7,9)
    which(X==4)

    ## [1] 2

    which.max(X)

    ## [1] 4

    which.min(X)

    ## [1] 1

Matrix
------

    matrix(1:6,nrow = 2)

    ##      [,1] [,2] [,3]
    ## [1,]    1    3    5
    ## [2,]    2    4    6

    matrix(1:6,ncol=2)

    ##      [,1] [,2]
    ## [1,]    1    4
    ## [2,]    2    5
    ## [3,]    3    6

    matrix(1:6,nrow=2,byrow = TRUE)

    ##      [,1] [,2] [,3]
    ## [1,]    1    2    3
    ## [2,]    4    5    6

    rbind(1:2,1:2)

    ##      [,1] [,2]
    ## [1,]    1    2
    ## [2,]    1    2

    cbind(1:3,1:3)

    ##      [,1] [,2]
    ## [1,]    1    1
    ## [2,]    2    2
    ## [3,]    3    3

Lists
=====

    List_data<-list("the",23.4,96,TRUE)
    List_data

    ## [[1]]
    ## [1] "the"
    ## 
    ## [[2]]
    ## [1] 23.4
    ## 
    ## [[3]]
    ## [1] 96
    ## 
    ## [[4]]
    ## [1] TRUE

    z<-list("Green","Yellow",c(2,4,7),TRUE)
    z

    ## [[1]]
    ## [1] "Green"
    ## 
    ## [[2]]
    ## [1] "Yellow"
    ## 
    ## [[3]]
    ## [1] 2 4 7
    ## 
    ## [[4]]
    ## [1] TRUE

Naming a List

    names(z)<-c("col1","col2","col3","col4")
    z

    ## $col1
    ## [1] "Green"
    ## 
    ## $col2
    ## [1] "Yellow"
    ## 
    ## $col3
    ## [1] 2 4 7
    ## 
    ## $col4
    ## [1] TRUE

Dataframes
==========

    dtr1<-c(1,2,3,4,5)
    dtr1

    ## [1] 1 2 3 4 5

    dtr2<-c("Sri","Rama","Ram","Sai","Siri")
    dtr2

    ## [1] "Sri"  "Rama" "Ram"  "Sai"  "Siri"

    dtr3<-data.frame(dtr1,dtr2)
    dtr3

    ##   dtr1 dtr2
    ## 1    1  Sri
    ## 2    2 Rama
    ## 3    3  Ram
    ## 4    4  Sai
    ## 5    5 Siri

Naming a Dataframe
==================

    names(dtr3)<-c("No's")
