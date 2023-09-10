# GIT #

echo "# commands" >> README.md <br/>
git init <br/>
git add README.md <br/>
git commit -m "first commit" <br/>
git branch -M main <br/>
git remote add origin https://github.com/Jaiminkapopara/{filename}.git <br/>
git push -u origin main <br/>

## Check Current Remote URL:
git remote -v <br/>

## Update Remote URL:
git remote set-url origin https://github.com/your-username/your-repo.git <br/>










# PRISMA #

npm install @prisma/client @auth/prisma-adapter <br/>
npm i prisma --save-dev <br/>
npx prisma init --datasource-provider mongodb(or other ) <br/>
npx prisma generate <br/>
npx prisma studio <br/>
