# Projects

DAT 530 Project 

Dashboard presentation on New England Storm Data Power BI

  . Transfered excel file to Power BI to create Dashboard
  . Validated Data using Power BI in order to ensure accuracy
  . Deaths and Injuries by category (Direct, Indirect Stacked Bar Chart)
  . Fluctuations in storm events by month (Most to least activity Ribbon Chart)
  . Storms by category (most to least by month Stacked Bar Graph)
  . Number of storms per month (most to least Bar Graph)
  . Cost of damages by category (Pie Graph)
  . Cost of damages by month (most to least Bar Graph)

D&D SPELL VISUALS 
. Found dataset using kaggle containing list of information for Dungeons and Dragons 5th Edition Spells
. Spreadsheet included -
      - Spell Name
      - Spell Description
      - Spell Level
      - Spell Schoool
      - Casting Time
      - Range
      - Duration
      - Class(es) capable of casting
      - Verbal Components (count)
      - Somantic compenents (count)
      - Material Components (count)
      - Material Components (description)
. Used Excel in order to validate all columns to ensure accuracy
. Created Dashboard in Power BI containing the following visusals
  - Count of Spells by Class (Donut Chart)
  - Sum of Spells that require components by class (Clustered Column Chart)
  - Count of spells by Class and School (Stacked bar chart)
  - Sum of spells by durattion (funnel chart)
  - Count of spells by cast time and class (Stacked Column Chart)
  - Count of spells by range and cast time (Stacked bar chart)

Titanic Sample Data
 - Received dataset from Excel regarding Titanic mortality rates consisting of the following columns
    - PassengerID
    - Survived
    - Pclass
    - Name
    - Sex
    - Age
    - Sibsp
    - Parch
    - Ticket
    - Fare
    - Cabin
    - Embarked
 - Validated Dataset using Excel in order to ensure accuracy of data
 - Converted '1, 0' values in Survival column to 'Yes' and 'No'
 - Converted '1, 2, 3' values to 'First Class, Second Class, Third Class' for Pclass file and changed column to 'Passenger Class' for clarity
 - Separated names into distinct columns and combined First, middle, and last name using Concatenate funciton
 - Corrected capitilization on Male and Female within Sex column
 - Added Age Group column using nested IF functions to distinguish 'Young', 'Young Adult', 'Adult' and 'Elder'
 - Converted any blank cells into average age to ensure minimal impact on data analysis
 - Renamed Sibsp and Parch to Sibling/Spouse and Parent/Children, then replaced with 'Family Aboard' by using SUM function on both columns
 - Added family details by using IF function where if Family Aboard column is greater than 0 'Family' if not, 'Alone'
 - Changed Ticket column to ticket number and formatted data as text rather than number to prevent errors.
 - Formatted Fare as Currency in order to prevent errors and round up decimals from original spreadsheet
 - Changed any blank cells in Cabin cell to N/A for clarity
 - Changed embarked data from 'Q', 'S', 'C' to 'Queenstown', 'Southhapton', 'Cherbourg', and 'N/A'
 - Created Visualizations using pivot tables including the following visuals
    - Count of Passenger Survival based on Gender (Bar Chart) 
    - Distribtuion of Revenue based on Port (Pie Chart) 
    - Count of passenger survival based on Class (Bar Chart)
    - Average age of survivors who travelled alone or with fameily (Bar Chart)
    - Breakdown of passengers who traveled alone or with fameily based on Gender (Stacked Column Chart) 
    - Survival rates based on departure port (Donut Graph)
