# banano-at-home

Docker-compose for Folding at home to get bananos


## Setting up

0. Install CUDA (and compatible nvidia driver).

1. Install Kalium wallet from Play store.

2. Go to https://bananominer.com/ to retrieve an user ID for Folding@Home.


## Configuration

Insert the user ID and team to `fah/config.xml`.


## Usage

In repo root:

    docker-compose up


Now you should see something like

    fah0_1  | 08:58:21:WU01:FS01:0xa8:Completed 59703 out of 5000000 steps (1%)


Bananos will be sent to your address tomorrow!
