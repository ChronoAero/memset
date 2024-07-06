### How to Start Building Your Version of Memset

After forking, please refer to the **TailwindCSS Executable** part of of the **Code Source Structure**. After installing the executable and running the command, all the files you need should be ready.

You can directly open each `.html` files on your browser and it will display normally as it would on a regular website.

For the instructions to manage the data in your page, please refer to the `/about` section of your site.

### Code Source Structure

#### TailwindCSS Executable
Please follow the instructions mentioned in [https://tailwindcss.com/blog/standalone-cli](https://tailwindcss.com/blog/standalone-cli). While working on the page, you may run the command

Please put the executable at the root of the project. I excluded it from the github repository as you can download it directly yourself (much like node_modules). 


```
./tailwindcss -i index.css -o out.css
```

to let tailwindcss generate the .css files needed for your styles. If you make changes to the name or the path of the .
css file, please adjust accordingly.


There is also a `tailwind.config.js` file if you need to configure tailwindcss' behaviour.

#### `.html` Files
You can put your .html files based on the root of the github pages directory, to put it into subpages, you can add a folder and insert the .html files there


`template.html` is for you to copy and create new pages quickly.

#### `.css` Files
You can put your .css files based on how you would like to access it from the .html files. By default, I linked it to `./out.css` in the root directory