# Clone the repository
git clone https://github.com/imglift/imglift-platform.git

# Navigate to project
cd imglift

# Install dependencies
npm install
# or
yarn install
# or
pnpm install

# Copy environment variables
cp .env.example .env.local

# Run database migrations
npx prisma migrate dev

# Start development server
npm run dev
