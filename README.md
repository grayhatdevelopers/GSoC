# GSoC 2025 Ideas

Grayhat pushes out a lot of open-source material every year, ranging from UI libraries, AI, and programming languages.
This year, our focus for GSoC will be on strengthening [UniversalPython](https://github.com/UniversalPython), a movement to bring multlilingual programming as part of the Python specification (through PEP).

## Project Ideas

* [Making Language Files More Robust](#making-language-files-more-robust)
* [Add More Human Languages to UniversalPython](#add-more-human-languages-to-universalpython)
* [Translate Error/System Messages with "How to Solve" Guidance](#translate-errorsystem-messages-with-how-to-solve-guidance)
* [Translating and Transpilation for Third-Party Libraries](#translating-and-transpilation-for-third-party-libraries)

---

## Making Language Files More Robust  

**Prerequisites:**  
- Experience with Python  
- Experience with YAML  
- Experience with Software Architecture  
- Experience with Internationalization Concepts  

**Description:**  
This project focuses on establishing a robust foundation for language definitions in UniversalPython by introducing standardization and basic configuration management.

**Key Objectives:**  

1. **Language Definition Standardization:**  
   - Design a standardized YAML-based format for defining language translations, including:
     - Keywords and built-in functions  
     - Special characters and numerical systems  
     - Right-to-left language support  
     - Language-specific punctuation marks  

2. **Configuration Management:**  
   - Engineer a flexible system for managing global transpilation settings, allowing easy modification of language-specific behaviors  

**Deliverables:**  
- Modular language files for easy addition of new languages  
- Unit tests to validate correctness  

**Difficulty:** Medium  
**Project Length:** 175 hours  

**Coding Mentors:**  
- [Abdurrehman Subhani](https://github.com/AbdurrehmanSubhani)  
- [Asfand Yar Aftab Raja](https://github.com/asfand687)  

**Assisting Mentor:**  
- [Syed Abdullah Nasir](https://github.com/NasirAbdullahSyed)  

---

## Add More Human Languages to UniversalPython  

**Prerequisites:**  
- Experience with Python  
- Experience with LLMs/Neural Networks  
- Experience with Prompt Engineering  

**Description:**  
Currently, UniversalPython supports only Hindi, Ukrainian, and Urdu through manually curated translation mappings. Instead of manually adding translations for more languages, this project aims to integrate a Large Language Model (LLM) for dynamic, AI-powered translations. The translations in most cases are not literal transaltion of a word hence the solution should take into account the context of the environment to generate the translation. The following languages will are required to be added:
- Chinese
- Russian
- Tamil
- French
- German

**Deliverables:**  
- Define rules and prompts for accurate translations of words.
- Develop a translation system which utilizes the power LLM's for UniversalPython 

**Difficulty:** Hard  
**Project Length:** 350 hours  

**Coding Mentors:**  
- [Abdurrehman Subhani](https://github.com/AbdurrehmanSubhani)  
- [Syed Abdullah Nasir](https://github.com/NasirAbdullahSyed)  

**Assisting Mentor:**  
- [Asfand Yar Aftab Raja](https://github.com/asfand687)  

---

## Translate Error/System Messages with "How to Solve" Guidance  

**Prerequisites:**  
- Experience with Python  
- Experience with Exception Handling  
- Experience with Localization  
- Experience with Abstract Syntax Tree (AST)  

**Description:**  
This project enhances UniversalPython by translating Python’s error and system messages into the developer’s preferred language (e.g., Urdu, Ukrainian, Hindi). Beyond translation, it also provides actionable troubleshooting guidance for each error, helping non-English speakers and beginners understand and resolve issues efficiently.
The system will dynamically analyze error messages and suggest potential solutions based on the error type and context, improving the debugging experience.

**Deliverables:**
- Error/system messages translated into the preferred language.
- Either in-compiler "How to Solve" guidance attached to each error message with actionable steps, or update documentation to cover these errors.
- Configurable fallback to English for troubleshooting.

**Difficulty:** Hard  
**Project Length:** 350 hours  

**Coding Mentors:**  
- [Syed Abdullah Nasir](https://github.com/NasirAbdullahSyed)  
- [Asfand Yar Aftab Raja](https://github.com/asfand687)  

**Assisting Mentor:**  
- [Abdurrehman Subhani](https://github.com/AbdurrehmanSubhani)  

---

## Translating and Transpilation for Third-Party Libraries  

**Prerequisites:**  
- Experience with Python  
- Experience with AST Manipulation  
- Experience with Dynamic Code Analysis  

**Description:**  
This project aims to build a framework to enable the translation of third-party Python libraries (e.g., NumPy, pandas) when used in UniversalPython. This would involve intercepting and transpiling third-party APIs into target languages. 
This system would also allow developers to use translated function names, parameter names, and documentation, making Python more accessible for non-English speaking programmers. A modular design will ensure that additional libraries can be supported with minimal effort. 

**Deliverables:**  
- Ability to translate function names, parameter names and documentation for common Python libraries.
- Modular design for adding new libraries.
- Configurable option to toggle between translated and original function names.
- Automation of the above, via LLMs and automation scripts
 
**Difficulty:** Hard  
**Project Length:** 350 hours  

**Coding Mentors:**  
- [Saad Ahmed](https://github.com/SaadBazaz)
- [Abdurrehman Subhani](https://github.com/AbdurrehmanSubhani)  

**Assisting Mentor:**  
- [Asfand Yar Aftab Raja](https://github.com/asfand687)  
- [Syed Abdullah Nasir](https://github.com/NasirAbdullahSyed)
