1. Create new project.

mkdir express-prisma-passport-project
cd express-prisma-passport-project

2. Initialize Node.js environment

npm init -y

3. Install dependencies

npm install express prisma @prisma/client passport passport-local bcryptjs express-session

4. Install dev dependencies

npm install --save-dev typescript ts-node @types/express @types/node @types/passport @types/passport-local @types/bcryptjs @types/express-session

5. Configure the TypeScript

npx tsc --init

6. Initialize Prisma

npx prisma init

7. Config Prisma schema in prisma/schema.prisma

8. Apply the migration

npx prisma migrate dev --name init