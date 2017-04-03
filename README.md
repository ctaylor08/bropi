# BROPI
Scripts to configure your Raspberry PI 3 (Raspbian) as a Wireless Access Point (WAP), and install:
- Bro 2.5 (Network monitoring)
- Apache Kafka (Log management +)
- Apache Spark (Eventual machine learning analytics)

At some point, I will also include a custom case design that will allow for additional SSH-enabled PIs (probably zeros) to be attached.

## Installing the things
So far, the only thing that I've got are scripts for bro and to setup your pi as a wap. I will be adding as I go.

To install the things, you can use the bropi_setup script as so:
```
# Install everything:
./bropi_setup

# Install specific things:
./bropi_setup wap
./bropi_setup bro
./bropi_setup kafka

# Kinda useless help message I threw in there:
./bropi_setup help
```

## TODO
- custom bro configs for master/proxy and workers
- install scripts for apache spark (and neccessary configs)
- case design for n? pi zeros added on as probably bro workers
- lots of other things
