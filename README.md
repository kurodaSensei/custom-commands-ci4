# Custom commands to create Controllers and Models in CI4

Custom commands to create controllers and models in Codeigniter 4, designed to facilitate the generation of base code for projects.

## Installation

For installation, you only need to clone this repository.

```bash
git clone https://KurodaSensei@bitbucket.org/KurodaSensei/custom-commands-ci4.git
```

## Usage
Once the files are downloaded, copy the Commands folder into the App directory of your CI4 project and voila, you can use the commands.

## Commands
Create Controllers
```bash
php spark make:controller UserController
```
It will create the **UserController.php** controller in the **App/Controllers** directory.

Create Controllers in a subdirectory
```bash
php spark make:controller Users.UserController
```
It will create the **UserController.php** controller in the **App/Controllers/Users** directory.

Create Resources Controllers
```bash
php spark make:controller --resource OR -r
```
It will create the **UserController.php** controller with common API methods REST (index, create, update, show, delete).

Create Models
```bash
php spark make:model User OR make:model User.User
```
It will create the **User.php** model in a **App/Model** directory or in **App/Model/User** directory


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)