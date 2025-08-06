# FafFrontend

This is intended as a helpful front end to a REST API to the US Bureau of Transportation Statistics (BTS) Freight Analysis Framework (FAF) dataset. It has been developed by the Data To Insight Center (D2I) at Indiana University as part of the [NSF ICICLE AI Institute](https://icicle.osu.edu/) and in collaboration with the US Department of Transportation's Bureau of Transportation Statistics. See [FAF-API-ICICLE](https://github.com/Data-to-Insight-Center/faf-api-ICICLE). This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.12.

The frontend utilizes the following version of the FAF dataset:

- **Most recent update:** December 18, 2023


**Tag:** Smart-Foodsheds, Food-Access

---
## How-To Guides

### 🌐 Accessing the Frontend

You can access the deployed Angular frontend at:

**[https://faffrontend.pods.icicleai.tapis.io/](https://faffrontend.pods.icicleai.tapis.io/)**


### 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)  
- [Angular CLI](https://angular.dev/tools/cli)  
  Install globally with:  
  ```bash
  npm install -g @angular/cli

### Installation
   ```bash
git clone https://github.com/Data-to-Insight-Center/faf-frontend-ICICLE.git
   ```
   ```bash
cd faf-frontend-ICICLE
   ```
   ```bash
npm install
   ```

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.


### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

---

##  Explanation

The Angular UI is structured around two primary sections: **Domestic Flow** and **Foreign Flow**, both accessible from the left-hand navigation menu. Each section is designed to support efficient exploration and analysis of freight data.

###  Domestic Flow

The **Domestic Flow** section contains two tabs:

#### 1. Domestic Import & Export
This tab allows for the generation of CSV files based on selected freight parameters. The following six fields must be specified via dropdown menus:

- Foreign Destination Mode  
- Commodity  
- Start Year  
- End Year  
- Origin  
- Destination  

Once these fields are selected, a CSV file can be generated containing the filtered data.

#### 2. State & Year Analysis
This tab presents state-level import and export data in the form of pie charts for a selected year, enabling quick visual analysis of freight distribution across states.


###  Foreign Flow

The **Foreign Flow** section includes two tabs:

#### 1. Foreign Import  
#### 2. Foreign Export  

These tabs mirror the functionality of the Domestic Import & Export section. Required values can be selected from the dropdown menus, and data can be exported in CSV format based on the selected criteria.

---

## License

FAF Frontend is developed by Indiana University and distributed under the BSD 3-Clause License. See [LICENSE](LICENSE) for more details.

---

## Acknowledgements

Thanks to colleagues at Texas Advanced Computing Center (TACC) who are hosting the FAF Frontend and at University of Wisconsin-Madison for organizing this work as part of the National Science Foundation under award #2112606, AI Institute for Intelligent CyberInfrastructure with Computational Learning in the Environment (ICICLE). Thanks to the US Bureau of Transportation Statistics for guidance.

---
## References
Freight Analysis Framework, Bureau of Transportation Statistics https://www.bts.gov/faf
