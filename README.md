# betternote
BetterNote android app
# BetterNote Project Overview

## Project Structure

### Branches
- **main**: Ultra stable version of the project.
- **dev**: Development branch for ongoing work.
- **feature**: Dedicated branch for feature development.

### Agenda
- **Monthly Goals[MARCH]**:
    - Web app / Android:
        - [ ] Create UI for note-taking.
        - [ ] Create a Note entering space.

    - **Week 1 Tasks**:
        - **Android Team**:
            - [x] Learn Kotlin UNIT 1.
            - Build a basic application.
                - [x] Set up Android Studio.
                - [x] Create a new Kotlin project.
                - [x] Display a simple "Hello World" message.

        - **Web Team**:
            - Basic code setup.
                - [x] Set up a new React project.
                - [x] Create a simple webpage.
                - [x] Understand the basics of HTML and CSS.

    - **Week 2 Tasks**:
        - **Android Team**:
            - [ ] Learn Android Development Unit 2
            - [ ] Go through Android Development Basics
            - [ ] Create a clock
            - [ ] Create a calculator(maybe?)

        - **Web Team**:
            - [ ] Add formatting functionality 
              - [ ] Research on markdown input
            - [ ] Key bindings (redo, undo, etc) support
            - [ ] Define routes for UI
            - [ ] Create sidebar and remove navbar
            - [ ] Basic todo functionality


### Tech Stack
- **Android App**: Kotlin
- **Frontend**: React

### Owners
- [abhishekcoder15](https://github.com/abhishekcoder15)
- [anantdark](https://github.com/anantdark)
- [i-akshay-kumar](https://github.com/i-akshay-kumar)
- [durgesh-code](https://github.com/durgesh-code)

## Checklists for Tasks

### Android Team (Week 1)
- [ ] Set up Android Studio.
- [ ] Create a new Kotlin project.
- [ ] Create an app to display a simple message.

### Web Team (Week 1)
- [ ] Set up a new React project.
- [ ] Create a simple webpage skeleton.
- [ ] Understand the basics of HTML and CSS.

### Common Features Implementation
- **Login Function (Basic)**
    - [ ] Implement a basic login form.
    - [ ] Create a user database mock.


- **Use JSON-like Structures/Files (v1)**
    - [ ] Learn about JSON syntax.
    - [ ] Create sample JSON data.


- **Note Taking**
    - **Supports Markdown (v1)**
        - [ ] Learn Markdown basics.
        - [ ] Implement a simple Markdown editor.

    - **Auto-save with timestamp (v1)**
        - [ ] Explore local storage in Android.
        - [ ] Implement auto timestamp-save functionality.


- **Todo List**
    - **Checklist (v1)**
        - [ ] Create a checklist component.
        - [ ] Implement adding items to the checklist.
        - [ ] Implement marking items as done from checklist.

    - **Reminder audio jingle (v1)**
        - [ ] Explore audio libraries for Android.
        - [ ] Implement basic audio functionality.

    - **Reminder notifications (v2)**
        - [ ] Understand Android notification system.
        - [ ] Implement notification feature.


- **Data Sync**
    - **Export of data (v2)**
        - [ ] Learn about data export formats (e.g., JSON).
        - [ ] Implement data export functionality.

    - **Import of data (v2)**
        - [ ] Implement data import functionality.
        - [ ] Ensure compatibility with exported data.
    
    - **Auto Sync feature(v3)**
      - [ ] DISCUSSION: sync between devices and merge conflict resolution.


- **Login Feature (v2)**
    - [ ] Implement on-device login functionality 
    - [ ] Implement credential hashing to secure passwords
    - [ ] Implement user authentication.


- **Encrypt Notes (v3)**
    - [ ] Research basic encryption concepts.
    - [ ] Implement note encryption and decryption.

- **Support Vim Keybindings (v4)**
  - [ ] Enable switch to activate vim-mode for notes
  - [ ] For todo enter will create the todo(no multiline todo)
