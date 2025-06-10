# DocsApps4x 

## Organization page

- In the organization page we create a **New Org** by clicking the + icon.

- The created Organization has Three icons (Options) :
 
1. **Organization**
2. **Environment**
3. **SystemHome**

### Chart Flow

                Organication
	                  ↓
    Environment (Test, Live Env)
				  ↓
		Test Environment
		    ↓
         Company (Company A, Company A1)

### Organization
Click the Organization and goto the Environment and here we create multiple _Environment_ like Test, live by cliking the + icon and filling the name field.

### Environment
In side the Environment we can create multiple **Company** by clicking the + icon and we can able to configure the basic Configure like change the theme, icons, title for the company.

### SystemHome
While clicking the SystemHome Icon it will redirect to the 1st company's Home page in the Environment.

## Company home page
In the stating the Home page has **Studio** app only, and the click the studio app it redirect to the **Welcome to Apps4x studio** page.

### Welcome to Apps4x studio page

In there we create apps by clicking the + icon at the right end side and fill the form like **Name, Image, url, Apptype, Title, Description, and prefix**.

#### There are different type of Apps and one connectors :
App Types:

	1. Apps
	2. Portals
	3. Website
	4. Mobile
	5. AppApi
	6. Workspace
	7. External

Connectors and its types:

	1. SQL
	2. MangoDB
	3. RestApi
	4. ApiMethod
	5. Swagger
we create connectors by selecte the connector first and click the + icon and fill the form like **Name, Image, connectorType**.	


### Apps (Feature now we have)
Apps means a application. Like Helpdesk, Customer support.

### Portals
A centralized web-based interface that provides access to multiple apps in one place.

**Diff BTW app and portal**:  
 An apps is like a tool.   
 And the portal is a toolbox - it holds many tools (apps) in one place for easy access.

 ### Website
 We create websites here.

 ### Mobile
 We create mobile app here.

 ### AppApi
 The AppApi is a backend process, and we create Api apps here.

 ### Connectors (Feature now we have)
 A connector is like a bridge that lets our application talk to another system or database.

 ### Workspace
 A workspace is your digital work area inside a software, where everything you need is organized, and ready to work.

 ### External
Intergrate the other Company's or Systems app to our system.

## Created app
Click the app we created in the studio (Welcome to Apps4x studio) page and it will redirect to the app settings(config) page.

### The core concepts in the settings config page:

1. Collection
2. Entity
3. Field
4. Field Groups
5. Form
6. Page
7. Menu

### Collection
Create the collection by clicking the + icon and fill the mantary fields. Then the collection was created. And add the Fields in the collection.

### Entity 
Create the entiry under the collection and add the Fields we already created in the collection. If you want add extra fields are not there in the collection Field then Create Fields by using **Client Field** option.

### Field
In the Collection and Entity both has a Field tab click the field tab and add the fields by filling the Forms and its fields like **Lable, Name, FieldType - _like Interger, String, Image, Date, DateTime, Dropdown, Relation(`Relation used to Related the fields to one to another entity field`), Button and ect_... - Readonly, Hide, Mandatory, Unique, Sequence ect...**

### Field Group
The Field Group tab is available only in the Entity. Its purpose is to group fields together. Whenever you want to use the grouped fields in another entity's field, you need to fill in the _Related List Field Group_ in the form field.

### Form
Form tab in Collection and entity but mostly we create the form in the entity because when we add the client fields in the Entity its not be there in the collection field so we creat forms in the entity.  

Forms has lot of Types but we moslty and mainly use **Table, List, Customtemplate, Workflow, Chart, Details(Create), Actions forms**.  

### Table Form
Create the form by clicking and filling the Name and Type fields. And click the **Table** Form Id Its goes to the details page there are five tabs **Configuration, Colums, DataSource, Sorting, Condition**.

#### Configuration Tab (Table Form)
In the configuration tab we configure the show create, show edit, show delete show export import option, view type and some other configurations.

#### Columns Tab (Table Form)
The columns tab displays the all fields we created in the fields tab if you dont want any of fields then delete the fields. In the right corner there was a settings icon, Click the icon and its opens a form the from contains _data type, view type, position, size, page view type, page type_ fields. We will configure a particular field here.

#### DataSource Tab (Table Form)
Select the DataSource type as RestApi and select get method then paste the Api. It will give the needed data through by the Api to the Entity's form. And we will get the data by Collections, Entity also by change the DataSource Type.

#### Sorting (Table Form)
Add a column and select the fields. The fields have sorting options.

_Where is it used?_  
When we create data such as names, ages, or tickets in the output app, each entry has an ID like (Ticket ID).
In the Studio app, we can add these fields and set their sorting order to descending.
Now, when we create a new name or ticket, the newly created entry appears at the top of the list. This is how sorting is mainly used.

#### Condition (Table Form)
We can add a single condition or group conditions using operators like AND and OR.  
Ex: In the My Assigned tickets in the helpdesk its shows the ticket assigned to me only in this place the condition is used.

### Details Form
Click the **Details** Form Id Its goes to the details page there are four tabs **Config, Design, Rules, DataSource**

#### Config
In the config tab we configure the Show Attach, action custome and view type (ex: list).

#### Design
Add the fields which is display in the output app create form.
And there is also a settings icon click the icon and a popup opens and we config the width, height, direction, alignment, lable position, field position(static, absolute, relative), hide lable of the **Create form**.

#### Rules
We create rules for Oninit, OnBeforeSubmit and OnAfterSubmit.

_Where is it used?_  
In the output app, forms can have Rules base dropdowns. For example, if the user selects the "Portal" category, a subcategory dropdown appears. If the user selects the "CRM" category, no subcategory is shown. This is where Rules are used.

#### DataSource
Select the DataSource type as RestApi and select get method then paste the Api. It will give the needed data through by the Api to the Entity's form. And we will get the data by Collections, Entity also by change the DataSource Type.













