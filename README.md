# _Patent Search - Information Retrieval NLP Project_

## File Overview 

- `python/`
    - All codefiles can be found in this directory
    - `data.py` is a script to collect data from Harvard's USPTO dataset
    - `testing_data.py` is a script to collect relevant results from google-patents
    - `system.py` contains most of the source-code for our custom IR system for patents
    - `score.py` is used to compare, evaluate, and provide metrics on our results and test/dev/train data

- `json/`
    - `dev/`
        - Contains data/relevant-docs/results/metrics for dev set
    - `test/`
        - Contains data/documents and metrics for test set
        - Utilizes manually annotated answer key

## Final Test Results
```json
{
    "average_precision": [
        {
            "query": "AI-Powered Personal Finance Management",
            "average_precision": 0.693262887905745,
            "nDCG": 0.7846853911965874
        },
        {
            "query": "Waste-to-Energy Conversion Technologies",
            "average_precision": 0.19140646526675936,
            "nDCG": 0.4683967562093268
        },
        {
            "query": "DNA Data Storage Technologies",
            "average_precision": 0.6501662406176011,
            "nDCG": 0.770490470865307
        },
        {
            "query": "Wearable Exoskeletons in Rehabilitation",
            "average_precision": 0.6779243030791019,
            "nDCG": 0.9575014298202769
        },
        {
            "query": "Underwater Robotics for Marine Research",
            "average_precision": 0.5762502001782187,
            "nDCG": 0.8694172437769564
        },
        {
            "query": "Autonomous Farming Machinery",
            "average_precision": 0.4917507646674313,
            "nDCG": 0.7768171665109933
        },
        {
            "query": "Voice Recognition Technology in Smart Homes",
            "average_precision": 0.5445126300428159,
            "nDCG": 0.8543731507549288
        },
        {
            "query": "Quantum Sensors in Navigation Systems",
            "average_precision": 0.266804989881913,
            "nDCG": 0.505673521700467
        },
        {
            "query": "Drone Delivery Systems in Logistics",
            "average_precision": 0.7761367807936437,
            "nDCG": 0.9174940836087776
        },
        {
            "query": "Artificial Photosynthesis for Carbon Capture",
            "average_precision": 0.5144294006013902,
            "nDCG": 0.7046996957324725
        }
    ],
    "MAP-Score": 0.538264466303462,
    "Mean nDCG": 0.7609548910176093
}
```