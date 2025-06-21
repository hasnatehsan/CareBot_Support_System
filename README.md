    # CareBot Assist 🤖💊

**CareBot Assist** is an AI-powered healthcare chatbot built with [Rasa](https://rasa.com/).  
It helps users book doctor appointments, log symptoms, and receive medication reminders.

## Features

- 📅 **Doctor Appointment Booking:** Schedule appointments with doctors.
- 📋 **Symptom Logging:** Log and track symptoms.
- ⏰ **Medication Reminders:** Set and get reminders for taking medications.

## Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/YOUR_USERNAME/CareBot_Assist.git
    cd CareBot_Assist
    ```

2. **Create and Activate Virtual Environment:**
    ```bash
    python -m venv rasa_env
    source rasa_env/bin/activate   # On macOS and Linux
    .\rasa_env\Scripts\activate    # On Windows
    ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Train the Model:**
    ```bash
    rasa train
    ```

5. **Run the Bot** (In separate terminals):
    ```bash
    rasa run
    rasa run actions
    ```

6. **Chat with the Bot:**
    ```bash
    rasa shell
    ```

## Custom Actions

- `action_book_doctor`: Books a doctor appointment.
- `action_log_symptoms`: Logs user symptoms.
- `action_remind_medication`: Sends medication reminders.

## Debugging

To see detailed logs and trace the bot's behavior, use:
```bash
rasa shell --debug


**Hasnat Ehsan** - Developer
