# MVC-Tutorial

Based on: https://www.tutorialspoint.com/mvc_framework

[![MVC pattern](imgs/model_view_controller.jpg)](#)  <!-- Image without link to  file-->

**Model:** Business logic-related data (from DB).  
**View:** UI (textboxes, dropdowns, etc.).  
**Controller:** Handles interactions and updates DB.  

**ASP.NET** supports three development models: Web Pages, Web Forms and MVC.

**Request/Response flow**  
The **browser** sends a request to the **MVC Application** which is received by the **Global.ascx** where is routed to a **Controller**, who forms a **Model** that is later passed to a **View** that is rendered to the **output**
