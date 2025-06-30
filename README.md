# photometric-redshift

tried (very amateur) to use 3 methods to predict the redshift, and hence the distance of galaxies

- Type Ia Supernovae: the critical mass at which a white dwarf will explode is roughly constant, so its real luminosity is roughly the same; distance can be calculated by comparing real luminosity and apparent luminosity seen from Earth
- Cepheid variable stars: found by Henrietta Swan Leavitt, the period of pulsation and average real luminosity of Cepheid variable stars follow a predictable relationship; distance is found again by comparing luminosities
- Photometric redshift: By observing the characteristic peaks in the starlight's spectroscopy the redshift can be determined, which in turn can be used to calculate the distance. However this is inefficient as spectroscopy requires long exposure so instead just find the amplitude of around 5 filters and feed it into a neural network to train and predict the redshift (code is in last page of PDF)

![image](https://github.com/user-attachments/assets/217ca266-3c10-4828-84c2-e2b48ecc3d40)

![image](https://raw.githubusercontent.com/toshinari123/photometric-redshift/main/poster.PNG)
