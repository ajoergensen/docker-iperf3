# iperf3 in a box

## Usage

### Run as server

`docker run -p 5201:5201 ajoergensen/iperf3 --server`

### Run as client

`docker run -it ajoergensen/iperf3 --client my.iperf.server`

### Other

Run `docker run ajoergensen/iperf3` for a complete list of iper3 options