name: Bug Report
description: Reportar un problema
title: "[Bug]: "
labels: ["bug"]
assignees:
  - 
body:
  - type: input
    id: contact2
    attributes:
      label: ¿Qué cliente lo solicita? 👁‍🗨
      placeholder: Lo solicita el cliente...
  - type: input
    id: contact
    attributes:
      label: Instancia 👨‍💻
      description: ¿En qué instancia ocurrió el problema?
      placeholder: INSTANCIA.ucontactcloud.com
    validations:
      required: false
  - type: checkboxes
    id: terms1
    attributes:
      label: Indicar el tipo de servidor 🗄
      options:
        - label: On-premise 🖥️
        - label: Cloud ☁
  - type: input
    id: version
    attributes:
      label: Versión 🔢
      description: ¿Cuál es la versión de uContact en la que ocurre el problema? (Poner número de versión)
      placeholder: 6.4xx
    validations:
      required: false
  - type: dropdown
    id: channel
    attributes:
      label: ¿En qué canales ocurre este problema? 🏷
      description: En caso de ser SMS indicar el proveedor en la descripción
      multiple: true
      options:
        - Voz
        - Webchat
        - SMS/Whatsapp
        - Email
        - Facebook/Messenger
  - type: textarea
    id: what-happened
    attributes:
      label: ¿Cuál fue el problema? 🐞
      description: Describir el problema lo más detalladamente posible 💬
      placeholder: Ocurrió un incidente al...
    validations:
      required: true
  - type: textarea
    id: logs
    attributes:
      label: Logs 🔡
      description: Copie y pegue el log. Este se formateará automáticamente como código.
      render: shell
  - type: textarea
    id: pasos
    attributes:
      label: Pasos para reproducir el incidente 👣
      description:  
      placeholder: 1- Primero se entra como supervisor a ...
  - type: checkboxes
    id: terms
    attributes:
      label: ¿Fue validado en otras instancias? ▶
      description: En caso de no haber sido reproducido agregar el label Triage 🏷
      options:
        - label: Si ✔
  - type: textarea
    id: multimedia
    attributes:
      label: En caso de disponer de capturas o videos, añadirlos aquí 📹
      description:
      placeholder: Adjunta aquí tu archivo multimedia... 
  - type: input
    id: contact1
    attributes:
      label: Plazos solicitados por el cliente 📅
      description: Mencionar plazos o fechas para estimar y priorizar
      placeholder: El cliente pide que se pase un estimativo antes de...
  - type: markdown
    attributes:
      value: |
        ##
        ### Recordar:
        #### - Agregar los labels involucrados en el problema 🏷
        #### - Seleccionar Projects-> To do 👉
        #### - Añadir capturas, imagenes y/o videos que ayuden al proceso de validación y desarrollo 📷📹🎞
        #### - Mencionar si el cliente tiene salida a internet 📶
        #### - Tipo de licencia 🔑
        ##
