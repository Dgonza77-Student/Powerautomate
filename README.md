# Powerautomate




## First adaptive card test/flow

<img width="601" height="242" alt="image" src="https://github.com/user-attachments/assets/2c32685c-a73f-41c0-8c2b-508c568ed700" />

Result:

<img width="615" height="453" alt="image" src="https://github.com/user-attachments/assets/d214a89f-f7e5-458f-9e9e-e53a370ceae2" />



Sharepoint list Example

<img width="1794" height="945" alt="image" src="https://github.com/user-attachments/assets/9a433cec-9007-482a-a6c5-c299349cc915" />



Updated flow

<img width="266" height="485" alt="image" src="https://github.com/user-attachments/assets/2a37b5b4-34a7-4165-88fa-315cbf6310b4" />

Working JSON code

```
JSON

{
  "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
  "type": "AdaptiveCard",
  "version": "1.4",
  "body": [
    {
      "type": "TextBlock",
      "text": "Weekly Update Form",
      "weight": "Bolder",
      "size": "Medium"
    },
    {
      "type": "Input.Text",
      "id": "projectNames",
      "placeholder": "Enter project name(s)",
      "label": "Project Name(s)"
    },
    {
      "type": "Input.Text",
      "id": "blockers",
      "placeholder": "Describe any blockers",
      "label": "Blockers",
      "isMultiline": true
    },
    {
      "type": "Input.Text",
      "id": "supportNeeded",
      "placeholder": "Describe any support needed",
      "label": "Support Needed",
      "isMultiline": true
    }
  ],
  "actions": [
    {
      "type": "Action.Submit",
      "title": "Submit"
    }
  ]
}
```


Graph example


<img width="619" height="320" alt="image" src="https://github.com/user-attachments/assets/cd71db33-8ef6-4db7-bd67-2bf03d082d19" />
