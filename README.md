# Analysis of Hotel Reviews from TripAdvisor

Herein, methods of data mining for text entries are applied using Pandas and Scikit-Learn, whilst being visualized through Matplotlib and Seaborn.

Besides mining the text entries, two machine learning methods are applied, these being Decision Tree and Random Forest.

The author emphasizes that it is still a work in progress and, as such, the models accuracy are yet to be improved.

#### In order to run this model in **Linux** follow these steps:

1. Create a virtual environment in your terminal using the code:

        python3 -m venv hotel_rev-venv

3. Activate the virtual environment you just created using:

        source hotel_rev-venv/bin/activate

5. Install the necessary packages in the activated environment using: 

        cat requirements.txt | sed -e '/^\s*#.*$/d' -e '/^\s*$/d' | xargs -n 1 python -m pip install

#### In order to run this model in **Windows** follow these steps:

This project utilizes a Python virtual environment named "classCD-venv" to isolate its dependencies. Follow the instructions below to set up the virtual environment on a Windows machine.

1. Open PowerShell as an administrator. To do this, right-click on the PowerShell icon and choose "Run as administrator."

2. Check the current execution policy of PowerShell with the following command:

    ```powershell
    Get-ExecutionPolicy
    ```

3. If the execution policy is not *RemoteSigned* or *Unrestricted*, you need to change it to allow script execution. Execute the following command:

    ```powershell
    Set-ExecutionPolicy RemoteSigned
    ```

    Confirm the policy change by responding with "Yes."

4. Navigate to your project directory using the `cd` command:

    ```powershell
    cd (Enter the path to the folder where the project files are located, without the parentheses)
    ```

5. Create a virtual environment using the following command:

    ```powershell
    python -m venv hotel_rev-venv
    ```

6. Activate the virtual environment:

    ```powershell
    .\venv-DRZ\Scripts\Activate
    ```

7. Ensure that 'pip' is up to date:

    ```powershell
    python -m pip install --upgrade pip
    ```

8. Install project dependencies:

    ```powershell
    pip install -r requirements.txt
    ```