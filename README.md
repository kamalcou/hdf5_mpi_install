# hdf5_mpi_install
# Steps
## to install hdf5 and openmpi together
sudo apt-get install -y libhdf5-openmpi-dev
//
 ls
//
git clone https://github.com/HDFGroup/Tutorial.git 
//
ls 
//
cd Tutorial/  //
  561  ls
  562  cd Parallel-hands-on-tutorial/
  563  ls
  564  ls -la
  597  make
  598  srun -n 4 ./h5par_ex0
  599  sudo apt install slurm-clinet
  600  sudo apt install slurm-client
  601  srun -n 4 ./h5par_ex0
  602  srun -n 2 ./h5par_ex0
  603  srun -n 1 ./h5par_ex0
  604  ln -s /usr/lib64/slurm/auth_munge.so /usr/local/lib/slurm/auth_munge.so
  605  mpirun -n 1 ./h5par_ex0
  606  ls
  607  mpirun -n 2 ./h5par_ex0
  608  mpirun -n 4 ./h5par_ex0
  609  mpirun -n 6 ./h5par_ex0
  610  mpirun -n 4 ./h5par_ex0
  611  mpirun -n 4 ./h5par_ex2e
  612  mpirun -n 4 ./h5par_ex2d
  613  h5dump h5par_ex2d.h5
  614  sudo apt install hdf5-tools
  615  h5dump h5par_ex2d.h5
  616  h5dump SDSpar.h5
