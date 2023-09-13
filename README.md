# hdf5_mpi_install
# Steps
## to install hdf5 and openmpi together
sudo apt-get install -y libhdf5-openmpi-dev  <br/>


## Download HDF5 files from github
git clone https://github.com/HDFGroup/Tutorial.git   <br/>

cd Tutorial/  <br/>


 cd Parallel-hands-on-tutorial/
 ls -la
 ## Run Make file to compile
 make
## Execute the file  
## Run with one rank
mpirun -n 1 ./h5par_ex0<br/>

ls<br/>
## Run with two ranks
mpirun -n 2 ./h5par_ex0<br/>
## Run with four ranks
mpirun -n 4 ./h5par_ex0 <br/>
## install hdf5 viewer
sudo apt install hdf5-tools <br/>

h5dump SDSpar.h5 <br/>

