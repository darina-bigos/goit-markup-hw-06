# goit-markup-hw-01

<picture>
                    <source
                      srcset="
                        ./images/portfolio-img-desk.jpg    1x,
                        ./images/portfolio-img-desk@2x.jpg 2x
                      "
                      media="(min-width: 1158px)"
                    />
                    <source
                      srcset="
                        ./images/portfolio-img-tab.jpg    1x,
                        ./images/portfolio-img-tab-@2x.jpg 2x
                      "
                      media="(min-width: 768px)"
                    />
                    <source
                      srcset="
                        ./images/portfolio-img-mob.jpg    1x,
                        ./images/portfolio-img-mob-@2x.jpg 2x
                      "
                      media="(max-width: 767px)"
                    />
                    <img
                      src="./images/portfolio-img-mob.jpg"
                      alt="portfolio pictxure"
                    />
                  </picture>

                  @media screen and (min-width: 768px) {

.hero-wrap {
background-image: linear-gradient(
rgba(46, 47, 66, 0.7),
rgba(46, 47, 66, 0.7)
), url(../images/hero-tab-bg.jpg);
}
@media (min-resolution: 2x){
.hero-wrap {
background-image: linear-gradient(
rgba(46, 47, 66, 0.7),
rgba(46, 47, 66, 0.7)
), url(../images/hero-tab-bg@2x.jpg);
}
}
}

@media screen and (min-width: 768px)

@media screen and (min-width: 1158px)

@media (min-resolution: 2x)
