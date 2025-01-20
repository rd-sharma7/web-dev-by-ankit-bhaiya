this is practical repo where experiment code has been written


## Installation of tailwind CSS 

install a tailwind css extension in vs code
create two folder distributor and src , then add the input.css file in src
create a tailwind.config.js using cmd "npx tailwindcss init"
add the below code in input.css to get suggestion of class

@tailwind base;
@tailwind components;
@tailwind utilities;

configure the path in config file , where in content section add path of html or content file
start tailwind , by use of input and output css cmd 
    npx tailwindcss -i ./src/input.css -o ./distr/output.css --watch 

link the output.css file in index.html
config file will be in root directory
