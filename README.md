# AI-data-generation


# Data Generation and CSV Export

This project generates sample data for different entities and saves them to CSV files.

## Dependencies

- Python 3.x
- pandas
- csv

You can install the required dependencies using pip:

```sh

pip install pandas
```


## Usage

To run the script, execute the following command:

**python** **main.py**

## Functions

### `save_data_to_csv(filename, data)`

This function saves the provided data to a CSV file.

* **Parameters:**

  * `filename` (str): The name of the CSV file.
  * `data` (list): The data to be saved.
* **Example:**

  **save_data_to_csv**(**'department_data.csv'**, department_data**)**

### `generate_data(entity, count)`

This function generates sample data for the specified entity.

* **Parameters:**

  * `entity` (str): The type of entity to generate data for (e.g., "department", "user").
  * `count` (int): The number of data entries to generate.
* **Example:**

  **department_data **=** generate_data**(**"department"**, **2**)

## Example Output

After running the script, you will find the following CSV files in your directory:

* `department_data.csv`
* `user_data.csv`
* `goals_data.csv`
* `feedback_data.csv`

Each file will contain the generated data for the respective entity.
