**1. Create a new project**
  - Go to [Console actions google](console.actions.google.com)
  - Click on *New project* button
  - Then enter a project name (here, for the tutorial I'll name it *actions-tuto*), choose a language (I'm going on *English*) and a pick a region of your choise
  - Select *Custom* card then press *Next*
  - Select *Blank project* card  then press *Start building*

**2. Setup**
  - On the *Develop* tab, set a *Display name* (for me it will be *magic test*) then hit *Save* button
  - Go in the *Webhook* tab (left menu), and paste your webhook here (I selected *HTTPS endpoint*) then *Save*
  - On the *Account linking* tab (left menu), active the *Account linking* switct, select *No* for linking with voice
  - For *Linking type*, select *0Auth* and *Authorization code* then press *Next*
  - Enter your *0Auth* informations then add your *Scopes*, to finish, *Write a description* of how to test your app

  **3. Logic**
  - Go to [This guide](https://developers.google.com/assistant/identity/google-sign-in) and follow it

  **4. Deploy**
  - Go to the *Deploy* tab, and enter:
    - Description (Short + Long)
    - Images (Banner + Icon)
    - Contact details (Mail + Name)
    - Privacy & Consent (Only privacy is needed)