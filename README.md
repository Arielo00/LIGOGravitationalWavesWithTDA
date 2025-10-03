# LIGOGravitationalWavesWithTDA
 Topological Data Analysis for gravitational waves in  the LIGO experiment


## Framework installation

Log into a linux machine with Anaconda installed.

In the terminal do:

1. Clone the repository:
  ```
  git clone git@github.com:Arielo00/LIGOGravitationalWavesWithTDA.git
  ```
2. Access the code:
  ```
  cd LIGOGravitationalWavesWithTDA
  ```

3. Install the conda enviroment:
  ```
  conda env create -f environment.yaml
  conda activate gravitational_wave_analysis
  conda develop .
  ```
  
3.1 Update the conda enviroment:
   ```
   conda env update --file environment.yaml --prune
   ```
