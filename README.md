# UIkit theming (material)


I don't like how you need to use Gulp to customize [UIkit](https://github.com/uikit/uikit) LESS so I arrived to the conlcusion that the method proposed below is the best method to compile less and keep peace of mind being able to update to the latest versions.

### Steps

1. bower install
2. create a folder with your project assets
3. add the customizations you need to asstes/less/uikit-core folder
4. you have to create all components separately and import it's parent first in order to compile them, you can add your customizations if needed
5. done, now you can complie uikit.less and uikit components with your favorite method, and also you can update using bower without lossing your customizations


### NOTES

You will see in assets/less/uikit-components/notify.leess I had to define a variable. I think it's a bug of the version 2.21.0

I arrived to the conclusion that customizinf from a UIkit theme, like almost-flat, is a nightmare because it seems they are not updated in every release

---

Hope this helps someone UIkit is a great FW but has a lack of tutorials and better documentation.


