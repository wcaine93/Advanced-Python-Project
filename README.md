# Advanced-Python-Project
> [!NOTE]
> Semester project for Advanced Python Programming course.

## Project Description
In this project, you will build a regression model using the deep learning TensorFlow and Keras library, and then you will experiment with increasing the number of training epochs and changing number of hidden layers and you will see how changing these parameters impacts the performance of the model.

### Project Format
This project is split into 6 different sections (files found in [src](src), full instructions in [Instructions](doc/Instructions.md)):
<ol type="A">
  <li>Import and process CSV data</li>
  <li>Split the data into training and test data</li>
  <li>Build a baseline NN model</li>
  <li>Normalize the data</li>
  <li>Increase the number of epochs</li>
  <li>Increase the number of hidden layers</li>
</ol>

## Results
| Metric | Baseline NN | NN + Normalized Data | NN with increased epochs | NN with increased hidden layers |
|:-:|:-:|:-:|:-:|:-:|
| Mean Squared Error | 137.66 | 115.09 | 71.599 | 94.966 |

## Data
The [concrete_data2.csv](src/data/concrete_data2.csv) dataset of 1301 records of concrete characteristics (features) and strength (target). After cleaning, [1005 records](src/data/concrete_data2.csv).
### Features
All numeric,
<table><thead>
  <tr>
    <td>Cement</td>
    <td>Blast Furnace Slag</td>
    <td>Fly Ash</td>
    <td>Water</td>
    <td>Superplasticizer</td>
    <td>Coarse Aggregate</td>
    <td>Fine Aggregate</td>
    <td>Age</td>
    <td></td>
    <td>Strength</td>
  </tr></thead>
</table>
