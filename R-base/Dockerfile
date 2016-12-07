FROM rocker/shiny

#install R dependencies
RUN  R -e "install.packages('devtools', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('httr', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('xts', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('shinydashboard', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('plyr', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('dplyr', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('reshape', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('flexdashboard', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('colourpicker', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('RCurl', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('doMC', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('foreach', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('ggplot2', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('dygraphs', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('googleVis', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('lubridate', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('scales', repos='http://cran.rstudio.com/')"
RUN  R -e "install.packages('uuid', repos='http://cran.rstudio.com/')"

#run server 
CMD ["/usr/bin/shiny-server.sh"]
