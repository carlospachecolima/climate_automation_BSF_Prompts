# climate_automation_BSF_Prompts
Step-by-step file for automating the generation of climate scenarios and engineering the prompts used
# Automated Climate Map Generation in QGIS and PyQGIS with AI-Supported Prompt Engineering

This repository demonstrates the use of prompt engineering combined with QGIS automation to generate climate change maps using PyQGIS and generative AI tools such as ChatGPT and GitHub Copilot. The main objective is to showcase how artificial intelligence can assist in automating geospatial workflows, especially in the context of climate data processing and cartographic layout generation.

## 🎯 Objective

To document and share the **automation workflow** and **prompt engineering techniques** used to generate climate maps from CMIP6 datasets. The focus is on transparency, reproducibility, and the integration of open-source geospatial tools with AI-driven scripting support.

## 🌍 Context

The process uses ACCESS-CM2 model outputs (WorldClim v2.1) for different IPCC SSP scenarios and time periods. The variables processed include:
- Maximum Temperature (Tmax)
- Minimum Temperature (Tmin)
- Precipitation (Prec)

Each script was developed iteratively through prompt-based interactions, aiming to automate:
- Raster clipping and band separation
- Renaming and styling
- Layout generation (.qpt)
- Map export in PNG format

## 📁 Repository Structure

- `scripts/`: Python scripts for QGIS automation
- `layouts/`: QGIS layout templates (.qpt)
- `outputs/`: Sample maps in PNG format
- `docs/`: Instructional documents and workflow guides
- `README.md`: Repository overview
- `LICENSE`: BSD-3-Clause license

## 🧠 AI Tools Used

- ChatGPT (for prompt-based scripting and logic development)
- GitHub Copilot (code completion and optimization)
- Google Colab (pretesting of code logic)

## 📘 Documentation

Full methodology, including prompt examples and figures, is available in:
`docs/Automated_Climate_Map_Generation_QGIS.docx`

## 👥 Authors

- Carlos Eduardo Pacheco Lima (Embrapa Hortaliças)  
- Marcus Aurélio Soares Cruz (Embrapa Tabuleiros Costeiros)  
- Júlio Roberto Araújo de Amorim (Embrapa Tabuleiros Costeiros)  
- Mariana Rodrigues Fontenelle (Embrapa Hortaliças)  

## 🛡️ License

This project is licensed under the CC BY 4.0 License – see the [LICENSE](LICENSE) file for details.
