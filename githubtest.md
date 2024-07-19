npm i typescript -g
tsc main.ts
tsc main.ts -w
tsc --init //initiate tsconfig
"rootDir": "./src", //source
"outDir": "./build/js",  // create js folder and save tempjs
tsc -w  //watch all
"include": ["src/**/*.ts"], in tscofig for avoind main.ts compailation


git config --global user.email "mayuran23412@gmail.com"
git config --global user.name "mayuran7732"

git remote remove origin
git remote add origin git@github.com:mayuran7732/test21.git

git push -u origin main


ssh
ssh-keygen -t rsa -b 4096 -C "mayuran23412@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa


cat C:\Users\kumaran\.ssh\id_rsa.pub
ssh -T git@github.com
