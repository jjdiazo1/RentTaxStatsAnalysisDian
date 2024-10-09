# RentTaxStatsAnalysisDian

[![License](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://github.com/ISIS1225DEVS/ISIS1225-Lib/blob/master/LICENSE)

## Overview

The **CorporateTaxAnalysis** project focuses on analyzing corporate tax statistics in Colombia, using data from the last 10 years provided by the DIAN (National Tax and Customs Office). This project involves working with unordered maps (hash tables), integrating concepts from linear data structures (lists, stacks, queues), search and sorting algorithms, and CSV data processing.

## Members

1. Student No. 1 Ángel Farfán, Student No. 1 Uniandes Email a.farfana@uniandes.edu.co, Student No. 1 20222183.
1. Student No. 2 Juan José Díaz, Student No. 2 Uniandes Email jj.diazo1@uniandes.edu.co, Student No. 2 202220657.
1. Student No. 3 Name Andrés Cáceres, Student No. 3 Uniandes Email a.caceresg@uniandes.edu.co, Student No. 3 202214863.

[Back to top](#corporatetaxanalysis)

## Context

In Colombia, corporate income taxes are levied on all revenues that contribute to an increase in a company's wealth. This project focuses on analyzing corporate tax data from DIAN over the past 10 years. Corporate taxes represent 78% of total tax revenue, with all companies, regardless of size, paying a flat tax rate of 35% on their profits.

### Data Loading

The dataset for this challenge comes from DIAN's statistical data on corporate tax revenues over the last 10 years. It includes CSV files with 59 variables related to companies' income, costs, assets, and taxes. The data is provided in files ranging from small subsets to full datasets, allowing for testing and implementation at different scales.

### References

1. [EAFIT - FAQ on Taxes](https://www.eafit.edu.co/escuelas/administracion/consultorio-contable/Paginas/faq-area-impuestos.aspx)
2. [DIAN - Corporate Tax Statistics](https://www.dian.gov.co/dian/cifras/Paginas/TributosDIAN.aspx)

## About the repository

This repository is part of the **Data Structures and Algorithms (EDA)** teaching framework at Universidad de los Andes. The repository was developed by faculty professors and staff in the Department of Systems and Computer Engineering (DISC) and uses the Non-Object-Oriented Python library **DISCLib**.

[DISClib](https://github.com/ISIS1225DEVS/ISIS1225-Lib) · [DISClib Demo and Examples](https://github.com/ISIS1225DEVS/ISIS1225-Examples) · [Report Bug](https://github.com/ISIS1225DEVS/ISIS1225-Lib/issues) · [Request Feature](https://github.com/ISIS1225DEVS/ISIS1225-Lib/issues)

## About The Project

**IMPORTANT** This is a work in progress and is part of a teaching framework for undergraduate college students at Universidad de los Andes. This project Is NOT intended as a full-functional source code project.

## Structure

The challenge template has four main parts:

1. [DISClib](https://github.com/ISIS1225DEVS/ISIS1225-Lib) Root folder with the official course library. For more on its implementation, visit the [DISClib Repository](https://github.com/ISIS1225DEVS/ISIS1225-Lib).
2. [App](./App) Folder with the model-view-controller (MVC) Python scripts. In here, the students implement their code to complete the challenge.
3. [Data](./Data) Folder with CSV data files to load into the application. Students must add the course-provided data files to complete the challenge.
4. [Docs](./Docs) Folder with reports, data tables, and other documentation. Students add their project report, data tables, and other documentation to complement their code implementation.

[Back to top](#corporatetaxanalysis)

## Requirements

### Requirement 1: Identify the economic activity with the highest tax liability (Group)

As a tax analyst, I want to identify the economic activity with the highest total tax liability (total balance due) for a specific economic sector and year.

### Requirement 2: Identify the economic activity with the largest tax credit (Group)

As a tax analyst, I want to identify the economic activity with the largest tax credit (total balance in favor) for a specific economic sector and year.

### Requirement 3: Find the economic subsector with the lowest total withholdings (Individual)

As a tax analyst, I want to find the economic subsector with the lowest total withholdings for a specific year.

### Requirement 4: Find the economic subsector with the highest payroll expenses (Individual)

As a tax analyst, I want to identify the economic subsector with the highest payroll expenses for a specific year.

### Requirement 5: Find the economic subsector with the highest tax deductions (Individual)

As a tax analyst, I want to identify the economic subsector with the highest tax deductions for a specific year.

### Requirement 6: Identify the economic sector with the highest total net income (Group)

As a tax analyst, I need to identify the economic sector with the highest total net income for a specific year.

### Requirement 7: List the top N economic activities with the lowest total costs and expenses for a subsector (Group)

As a tax analyst, I need to list the top N economic activities with the lowest total costs and expenses for a subsector and a specific year.

### Requirement 8 (Bonus): List the top N economic activities with the highest tax liabilities (Group)

As a tax analyst, I need to identify the top N economic activities, in each economic subsector, with the highest total tax liabilities for a specific year.

[Back to top](#corporatetaxanalysis)

## Usage

To use this template, you need to follow the steps below:

* Read the official project document published in the course official site at [BrightSpace](https://bloqueneon.uniandes.edu.co/d2l/home).
* Distribute the project functionalities and implementation responsibilities among the group members.
* Download the official dataset for the project at the course official site at [BrightSpace](https://bloqueneon.uniandes.edu.co/d2l/home).
* Unzip and load the dataset into the application at the [Data](./Data) folder.
* Import the necessary modules from [DISClib](https://github.com/ISIS1225DEVS/ISIS1225-Lib) into the MVC scripts at the [App](./App) folder.
* Implement the missing functions according to the project needs in the MVC scripts at the [App](./App) folder.
* Evaluate the implementation of the MVC scripts, record your tests and analysis in the documents at the [Docs](./Docs) folder (The report **MUST BE** in PDF format).

[Back to top](#corporatetaxanalysis)

## Contact and support

For further information and contact, use the following links:

* Official Repository [DISClib](https://github.com/ISIS1225DEVS/ISIS1225-Lib).
* Repository for [Demo and Examples](https://github.com/ISIS1225DEVS/ISIS1225-Examples).

If you require further information, please contact us [via this email](mailto:isis1225@uniandes.edu.co).

[Back to top](#corporatetaxanalysis)

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this project better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

[Back to top](#corporatetaxanalysis)

## License

Copyright 2020, Departamento de sistemas y Computación, Universidad de Los Andes.
Developed for the class _"ISIS1225 - Estructuras de Datos y Algoritmos"_ or _"ISIS1225 - Data Structure and Algorithms"_ in English.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/licenses/) for more information.

[Back to top](#corporatetaxanalysis)

## Authors and acknowledgment

* [Dario Correal](https://github.com/dariocorreal) is the original author and main developer of the library.
* [Santiago Arteaga](https://github.com/phillipus85) is a contributor and repository administrator. 
* [Luis Florez](https://github.com/le99) is a contributor and developed examples and tutorials for the library.

[Back to top](#corporatetaxanalysis)
