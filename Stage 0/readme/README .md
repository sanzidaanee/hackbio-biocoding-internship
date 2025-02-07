
# Topics: Coding Syntax, Data types, and Data Structures

@Slack: @Sanzida, @ Bez, @Tatiene,  @Hana, @Onyinye


## Task

In stage 0 the task is to organize the following information of the team members (names, slack names, emails, hobbies, countries, discipline, and preferred programming languages) using a simple data structure using R or Python.

## Dictionaries in Python

A dictionary is a data structure that stores the data values in key-value pairs. The values can be repeated and used in any type of data, whereas the key represents a specific piece of information like an email or name and cannot be repeated and must be used with immutable data types like strings, integers, and tuples. The values are accessed using the keys. Dictionaries are written with curly brackets.

When we input multiple values, we can store them as a list within the dictionary.

## How to Create a Dictionary

A dictionary can be created by placing an order of elements within curly braces {} and separated by a comma.

## Nested Dictionary

A nested dictionary means putting a dictionary inside another dictionary. To input all the information for the group of people together, we will create a nested dictionary. Nested dictionaries can be created by placing comma-separated dictionaries enclosed with braces.







### Create Dictionary for Group Information

```bash
  team_info= [
    {
        "Name": "Kazadi Ngoie",
        "Slack Username": "@Tatiene",
        "Email": "tatianangoie17@gmail.com",
        "Hobby": "Gaming",
        "Country": "South Africa",
        "Discipline": "Bioinformatics",
        "Preferred Language": "Python"
    },
    {
        "Name": "Bezaleel Akinbami",
        "Slack Username": "@Bez",
        "Email": "bezaleelakinbami16@gmail.com",
        "Hobby": "Gaming",
        "Country": "Nigeria",
        "Discipline": "Bioinformatics ",
        "Preferred Language": "R"
    },
    {
        "Name": "Hana Nadir",
        "Slack Username": "@Hana",
        "Email": "hananadir04@gmail.com",
        "Hobby": "Reading",
        "Country": "Sudan",
        "Discipline": "Medecinal chemistery and drug discovery",
        "Preferred Language": "Python"
    },
    {
        "Name": "Onyinye Maryrose Ugwu ",
        "Slack Username": "@Onyinye",
        "Email": "monyinye80@gmail.com",
        "Hobby": "Travelling",
        "Country": "Nigeria",
        "Discipline": "Zoology",
        "Preferred Language": "Python"
    },
    {
        "Name": "Sanzida Akhter Anee",
        "Slack Username": "@Sanzida",
        "Email": "aneesanzidaakhter@gmail.com",
        "Hobby": "Blogging",
        "Country": "Bangladesh",
        "Discipline": "Bioinformatics",
        "Preferred Language": "Python"
    }
]
```

### Print Information in Structured way

```bash
  print("Team Members Information:\n")

for member in team_info:
    print(f"Name: {member['Name']}")
    print(f"Slack Username: {member['Slack Username']}")
    print(f"Email: {member['Email']}")
    print(f"Hobby: {member['Hobby']}")
    print(f"Country: {member['Country']}")
    print(f"Discipline: {member['Discipline']}")
    print(f"Preferred Language: {member['Preferred Language']}")
    print("-" * 40)  # Separator for better readability

```


