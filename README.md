# MBTS4MA

This project provides the source code for the MBTS4MA tool. It aims to support the model-based testing of mobile apps developed for the Android platform. 

It is the main result of the master thesis of Guilherme de Cleva Farto, supervised by Andre Takeshi Endo.
UTFPR - Campus Cornelio Procopio - Brazil 

Publication:
```
@InProceedings{FartoEndo2017SBES,
    author = "G. C. Farto and A. T. Endo",
    title = "Reuse of model-based tests in mobile apps",
    booktitle = "Proceedings of the 31st Brazilian Symposium on Software Engineering (SBES)",
    year = "2017", 
    numpages = {10},
    location = {Fortaleza, Brazil},
} 
```

# Folders

- MBTS4MA-Runner: source code for the event runner that supports the test execution.
- MBTS4MA: source code for the tool.
- stereotypes: it contains the list of stereotypes implemented by the tool.
- templates: it contains code snippets and utility classes used in the stereotypes.
- usage: it contains an example.

# How to execute

- Clone the repository using "git clone"
- Import folders MBTS4MA and MBTS4MA-Runner as Eclipse projects
- Run class com.general.mbts4ma.Main.java of the MBTS4MA project
