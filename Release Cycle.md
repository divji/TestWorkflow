1 - I have 2 branches, master and develop
2 - I create a new feature branch from develop. Once I am done with my feature, I merge it into develop
3 - I keep doing this till I am done with all the features for the next release and now I am ready to release
4 - I create a new branch called release 0.1.0 from the develop where I do my final testing
5 - if everything is ok, I change the version in my config in the release branch from 0.0.0 to 0.1.0 and commit to the release branch
6 - then I checkout master and merge release 0.1.0 into it
7 - I also checkout develop and merge release 0.1.0 into it
8 - I delete release 0.1.0 branch once everything is successful
