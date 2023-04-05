### Instalações extras dos pacotes do R

##### Pacote *arrow*

Para instalação do pacote arrow, é necessário seguir os seguintes passos, como descrito no [documento](https://arrow.apache.org/docs/r/) do pacote:

```
install.packages("arrow")
arrow::install_arrow()
```

##### Pacote *hrbrthemes*

Em ambientes **Debian** ou **Ubuntu**, rode os comandos no terminal: 

```
sudo apt update
sudo apt install libfontconfig1-dev 
sudo apt install libcairo2-dev 
```

##### Pacote *mongolite*

Em ambientes **Debian** ou **Ubuntu**, rode os comandos no terminal: 

```
sudo apt update
sudo apt install -y libssl-dev libsasl2-dev 
```

Para outros ambientes, consulte o github do pacote: https://github.com/jeroen/mongolite

##### Pacote *pkgdown* - Dependência para o devtools

Em ambientes **Debian** ou **Ubuntu**, rode os comandos no terminal: 

```
sudo apt update
sudo apt install libfontconfig1-dev libharfbuzz-dev libfribidi-dev
```

##### Pacote *rJava*

Em ambientes **Ubuntu**, rode os comandos no terminal: 

```
sudo apt install -y default-jre
sudo apt install -y default-jdk
sudo R CMD javareconf
```

[Installing rJava on Ubuntu](https://www.r-bloggers.com/installing-rjava-on-ubuntu/)

##### Pacote *rstan*

Em ambientes **Ubuntu**, rode os comandos no terminal: 

```
sudo add-apt-repository -y "ppa:marutter/rrutter3.5"
sudo add-apt-repository -y "ppa:marutter/c2d4u3.5"
sudo apt update
sudo apt install r-cran-rstan
```

[Installing RStan on Linux](https://github.com/stan-dev/rstan/wiki/Installing-RStan-on-Linux)

##### Pacote *sf*

Em ambientes **Ubuntu**, rode os comandos no terminal: 

```
sudo apt update 
sudo apt install libudunits2-dev libgdal-dev libgeos-dev libproj-dev 
```

Ou passando o repositório: 

```
sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable
sudo apt update
sudo apt install libudunits2-dev libgdal-dev libgeos-dev libproj-dev 
```

Para outros ambientes, consulte o github do pacote: https://github.com/r-spatial/sf
