# 🐮🐕 Pasu Pālaṇā (Animal Care)

❤️ *Compassionate care through innovative technology*

---

<p align="center">
  <img src="https://media.giphy.com/media/UVqus6TxDWbfsDc4jM/giphy.gif" alt="Pasu Pālaṇā Banner">
</p>

## 🔗 Introduction

**Pasu Pālaṇā** (पशु पालणा) is a project dedicated to enhancing the management of shelters and gaushalas that care for abandoned and neglected animals. With a focus on technology-driven solutions, it empowers caretakers to efficiently track critical details about the animals they serve, such as health records, disease histories, treatments, and overall well-being.

---

## 🎯 Project Objective

Animals like cows, goats, and others are often abandoned when they are no longer "useful" to humans, left to suffer from disease or hunger. Gaushalas and animal shelters tirelessly save and care for these animals but lack efficient tools for record management. 

### Goals:
- 📝 **Track animal details**: Species, breed, gender, and health status.
- ⚕️ **Monitor health**: Disease history, treatments, and medical updates.
- 🔄 **Ease of use**: Simple and intuitive interface for caretakers.
- 🏆 **Scalability**: Expandable for features like adoptions, volunteers, and donations.

---

## 🔬 Key Features

### 🐘 Animal Records Management
- Tracks all animals in the shelter.
- Includes details like species, breed, gender, health history, and current status.

### ⚕️ Health and Treatment Monitoring
- Logs disease history and treatments for each animal.
- Ensures detailed medical tracking for better care.

### 📊 Database Connectivity
- Built using **Flask SQLAlchemy** with a **MySQL backend** for efficient data storage and retrieval.

### 🌈 User-Friendly UI
- Clean and simple interface for shelter staff to easily add, view, and update records.

---

## 🛠️ Technology Stack

| Technology       | Purpose                           |
|------------------|-----------------------------------|
| 🔧 **HTML & CSS**  | User interface development      |
| 🔧 **Python (Flask)** | Backend server-side logic        |
| 🔧 **Flask SQLAlchemy** | ORM for database interaction      |
| 🔧 **MySQL**        | Database for storing records     |

---

## 🔠 Project Structure

```
Pasu-Palana/
|-- static/
|   |-- images/          # Place project-related images here
|-- templates/           # HTML templates for the UI
|-- app.py               # Main Flask application
|-- config.py            # Database configuration
|-- requirements.txt     # Dependencies
|-- README.md            # Project documentation
|-- uploads/             # Directory for uploaded files (if any)
```

### Placeholder for Images
Add the following images in the `static/images/` folder to illustrate the project:

1. **Front Page**:
   ![Front Page Screenshot](static/images/front_page.png)
2. **Form Page** (Animal Data Entry):
   ![Form Page Screenshot](static/images/form_page.png)
3. **View Records Page**:
   ![View Records Screenshot](static/images/view_records.png)
4. **Database View** (MySQL data storage):
   ![Database Screenshot](static/images/database_view.png)

### Video Demo
- Include a video walkthrough of the project:
  [Project Demo Video](https://example.com/demo-video)

---

## 🌍 Impact

1. ⏳ **Efficiency**: Enables shelters to focus on animal care instead of manual data management.
2. 📚 **Accountability**: Ensures transparency in animal welfare tracking.
3. 📊 **Scalability**: Supports future features like adoption records, volunteer management, and donations.
4. ❤️ **Ethical Responsibility**: Promotes compassion for animals, aligning with values of humanity.

---

## 🚀 Vision

*"Technology can be a force for compassion."*

**Pasu Pālaṇā** demonstrates how simple tech solutions can significantly improve animal welfare. By combining the simplicity of Flask with robust database management, this project aspires to make a meaningful difference in the lives of countless animals.

---

## 🔧 Setup Instructions

### Prerequisites
- Python 3.8+
- MySQL Server

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/pasu-palana.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pasu-palana
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure the database:
   - Create a MySQL database named `pasu_palana`.
   - Update database credentials in `config.py`.
5. Run the application:
   ```bash
   flask run
   ```
6. Access the app at:
   [http://localhost:5000](http://localhost:5000)

---

## 💛 Contributing

We welcome contributions to improve **Pasu Pālaṇā**! 

### How to contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 🙏 Acknowledgments

Special thanks to all the caretakers and shelters who tirelessly work to make the world a better place for animals. 

---

## 🌐 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🔔 Stay Connected

- 📧 Email: [support@pasupalana.org](mailto:support@pasupalana.org)
- 🔗 Website: [www.pasupalana.org](http://www.pasupalana.org)
- 💌 Social Media: [Follow us on Twitter](http://twitter.com/pasupalana)

---

*Developed with 💖 by a team that cares.*
