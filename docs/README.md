# Tienda en base a **Xiaomi-store.co**

 Store-theme-Xioami fue desarrollada con la tecnologia de Vtex IO
 
 La tienda a imitar en este caso fue https://www.xiaomi-store.co/ donde se replico cada uno de sus componentes, en cada una de las vistas disponibles (desktop, Mobile y Tablet)

 ## **Recopilacion de Imagenes**
### **Vista Desktop**
#### Home 
<br/>
 
![Esta es una imagen de ejemplo](https://i.ibb.co/r7snDbC/Fire-Shot-Capture-005-marlon-itgloberspartnercl-myvtex-com.png") 

### Product detail page
![Imagen de Prodct Detail Page](https://i.ibb.co/3FCFQYQ/PDP.png)

### Product list page
![Imagen Product list page](https://i.ibb.co/3pRbKwR/PLP.png)

### Minicart 
![Imagen minicart](https://i.ibb.co/DkWHBKc/Minicart.png) 

### Menu 
![Imagen Menu](https://i.ibb.co/zSg1WcH/Menu.png)


## Configuration

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

## Workspace
* https://marlon--itgloberspartnercl.myvtex.com/

## Components Custom
* https://github.com/mguz29/vuitg-whatsapp-buttom-xiaomi-storehttps://github.com/mguz29/vuitg-whatsapp-buttom-xiaomi-store

* https://github.com/mguz29/vuitg-bullets-diagramation-xiaomi-store

# Contributors
1. Marlon Guzman Acosta
