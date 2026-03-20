# run instructions

## local

```bash
swashrun -input lima -mpi 8 > swashout &
```

## cloud

```bash
docker run --rm -v .:/home/swash delftwaves/swash swashrun -input  lima -mpi 8 > swashout &
```

## HPC cluster

```bash
# pull the image
apptainer pull docker://delftwaves/swash:latest

# run the container
apptainer run swash_latest.sif swashrun -input  lima -mpi 8 > swashout &
```
