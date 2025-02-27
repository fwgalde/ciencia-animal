# 🐑 Sheep Milk Production Prediction

Data science project to predict milk production in sheep using environmental, management, and biological variables. Based on the analysis of factors described in the document [variables.md](references/variables.md).

---

## 📂 Project Structure

This project is organized into the following main directories and files. As the project progresses, additional files and directories will be added:

1. **data/**: This folder will eventually contain all data-related files.

2. **notebooks/**: This folder will contain Jupyter Notebooks for data analysis, experimentation, and model training.

3. **models/**: Once models are trained, this directory will store final models.
   
4. **docs/**: This folder will eventually include all documentation related to the project.

5. **test/**: This directory will contain unit test scripts and test data to ensure that the project code works as expected and that the models are functioning correctly.

6. **references/**: This folder will store articles, studies, and other resources that provide background and context for the project.

7. **src/**: This folder will contain the core source code, divided into modular scripts for different tasks.

8. **requirements.txt**: This file will list all the Python dependencies required for the project, allowing others to easily install them by running `pip install -r requirements.txt`.

---

## 📊 Key Variables

Based on the provided study:

- **Temporal Variables**: Date and month of birth, milking days.
- **Environmental Variables**: Temperature, humidity, ITH, wind, solar radiation, precipitation.
- **Management Variables**: Pen space, location (park/corral), milking frequency.
- **Biological Variables**: Breed, live weight during lactation.

---

## 🤝 Contributing

1. Fork the repository.
2. Create a branch for your feature: `git checkout -b new-feature`.
3. **Follow the commit conventions**: Make descriptive commits that follow the [Commit Message Convention](https://www.conventionalcommits.org/en/v1.0.0/). For example: `git commit -m "feat: add ITH preprocessing step"`.
4. Push the branch: `git push origin new-feature`.
5. Open a Pull Request detailing your changes.

---

## 📄 License

This project is licensed under the [GNU GENERAL PUBLIC LICENSE, Version 2, June 1991](LICENSE).
