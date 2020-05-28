# NTU High-Performance Big Data and Artificial Intelligence Systems Homework

## 用linux裝R

    sudo add-apt-repository 'deb https://cloud.r-project.org/bin/linux/ubuntu bionic-cran40/'
    sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
    sudo add-apt-repository 'deb [arch=amd64,i386] https://cran.rstudio.com/bin/linux/ubuntu xenial/'
    sudo apt-get install r-base
#### 裝packages
先裝remotes

    install.packages("remotes")
再裝bigstatsr

    remotes::install_github(“privefl/bigstatsr”)
    remotes::install_github(“privefl/bigsnpr”)
#### 安裝vtune