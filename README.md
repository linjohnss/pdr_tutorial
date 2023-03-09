# PDR Tutorial
> Contribute by NCKU Point Lab

## Getting start

1. Install the required libraries.
- install conda
- build conda environment:
    ```shell
    conda env create -f requirements/environment.yml
    ```
2. Select the config file
``` yaml=
DATA_Path:
  data_folder: "./data/"
  input_name: "imu.csv"
  output_name: "output_PDR.txt"

PDR_Parameter:
  frequence: 25
  g: 9.80665
  user_height: 1.70
  init_heading: 0.0
  init_E: 0.0
  init_N: 0.0
```