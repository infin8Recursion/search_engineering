# Week1 Results


## Level1:

### Fields and Schema
* @bbuy_products.json
  * INFO:Done. 1275077 were indexed in 1.2091395283333441 minutes.  Total accumulated time spent in `bulk` indexing: 6.808180184999583 minutes

* @bbuy_products_no_map.json 
  * INFO:Done. 1275077 were indexed in 1.2331056800000018 minutes.  Total accumulated time spent in `bulk` indexing: 6.509632656667266 minutes

* @bbuy_products.json + extra fields 
  * INFO:Done. 1275077 were indexed in 4.936917511666676 minutes.  Total accumulated time spent in `bulk` indexing: 9.125661966667424 minutes

* @bbuy_products_no_map.json + extra fields 
  * INFO:Done. 1275077 were indexed in 4.699887493333335 minutes.  Total accumulated time spent in `bulk` indexing: 7.4837230566658945 minutes


### Index Settings
* @bbuy_products_no_map.json + -1
  * INFO:Done. 1275077 were indexed in 0.7939510750000106 minutes.  Total accumulated time spent in `bulk` indexing: 2.6237021550005313 minutes
* @bbuy_products_no_map.json + 1 second 
  * INFO:Done. 1275077 were indexed in 0.723906738333335 minutes.  Total accumulated time spent in `bulk` indexing: 2.468320886667122 minutes
* @bbuy_products_no_map.json + 60 seconds
  * INFO:Done. 1275077 were indexed in 0.7201747800000097 minutes.  Total accumulated time spent in `bulk` indexing: 2.546580031667266 minutes


### Threads and Batch Size
#### Batch Size

1) 400:  INFO:Done. 1275077 were indexed in 0.6563262416666779 minutes.  Total accumulated time spent in `bulk` indexing: 1.8614522149997963 minutes
2) 800:  INFO:Done. 1275077 were indexed in 0.9423005933333115 minutes.  Total accumulated time spent in `bulk` indexing: 2.1970719866668635 minutes
3) 1600: INFO:Done. 1275077 were indexed in 0.7132866283333593 minutes.  Total accumulated time spent in `bulk` indexing: 1.8826822266658079 minutes
4) 3200: INFO:Done. 1275077 were indexed in 0.6903000416666752 minutes.  Total accumulated time spent in `bulk` indexing: 1.8444644133336623 minutes
5) 5000: INFO:Done. 1275077 were indexed in 0.6766348883333194 minutes.  Total accumulated time spent in `bulk` indexing: 1.7824603800006116 minutes


#### Workers
1) 8:  INFO:Done. 1275077 were indexed in 0.8833471116666564 minutes.  Total accumulated time spent in `bulk` indexing: 3.072312411665856 minutes
2) 16: INFO:Done. 1275077 were indexed in 0.5055429549999947 minutes.  Total accumulated time spent in `bulk` indexing: 3.188570200000474 minutes
3) 32: INFO:Done. 1275077 were indexed in 0.4761904033333242 minutes.  Total accumulated time spent in `bulk` indexing: 7.957051371667331 minutes
4) 61: INFO:Done. 1275077 were indexed in 0.9690897549999742 minutes.  Total accumulated time spent in `bulk` indexing: 41.81883539333382 minutes

## Level2:
### Baseline
INFO:Finished running 10000 queries in 1.622956780000004 minutes

### Changes:
1) INFO:Finished running 10000 queries in 1.3328580000000025 minutes
2) INFO:Finished running 10000 queries in 1.0317564733333409 minutes
3) INFO:Finished running 10000 queries in 0.7052466433333393 minutes
4) INFO:Finished running 10000 queries in 0.5942579783333106 minutes
