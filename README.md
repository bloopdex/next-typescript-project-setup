# Next.js Project Template with Tailwind CSS
This is a project template for creating Next.js applications that use Tailwind CSS for styling.

## Getting Started
To get started, clone this repository and install the dependencies using npm:

```bash
git clone <repository-url>
cd <project-name>
npm install
```

## Development
To start a development server, run the following command:

```bash
npm run dev
```
This will start a development server at [local server](http://localhost:3000).

## Building for Production
To build the application for production, run the following command:

```bash
npm run build
```
This will build the application and generate static files in the out directory.

## Running the Production Build
To run the production build, run the following command after building the application:

```bash
npm start
```
This will start a production server at [local server](http://localhost:3000).

## Customization
This project template includes Tailwind CSS configured to use the jit mode by default. To customize the styles, edit the tailwind.config.js file.

Iconsax icons are also included in this template. To use them, import the desired icon from iconsax-react:

```jsx
import { IconName } from 'iconsax-react'

function MyComponent() {
  return (
    <div>
      <IconName />
    </div>
  )
}
```

You can also add additional dependencies and configuration to the project by editing the package.json file.

### Credits
This project template was created by [Your Name] using the following technologies:

- Next.js
- Tailwind CSS
- npm