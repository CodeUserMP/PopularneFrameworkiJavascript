# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Popularne frameworki JavaScript

React to biblioteka JavaScript stworzona przez Facebooka (obecnie Meta), służąca do budowania interfejsów użytkownika, a konkretnie dynamicznych, interaktywnych komponentów w aplikacjach internetowych. Jest często używany do tworzenia aplikacji jednostronicowych (SPA), gdzie większość interakcji odbywa się na jednej stronie, a nowe treści są ładowane dynamicznie, bez przeładowania całej strony.

## Podstawowe cechy Reacta

1. Komponenty:
     - React wprowadza koncept komponentów, które są podstawowymi blokami budowy aplikacji. Komponenty mogą być  funkcjonalne (oparte na funkcjach) lub klasowe (oparte na klasach ES6).
     - Każdy komponent może mieć swój własny stan (state) i może przyjmować dane wejściowe w postaci propsów (properties).
  
2. JSX (JavaScript XML):
     - JSX to składnia pozwalająca na pisanie elementów HTML wewnątrz kodu JavaScript. Jest to wygodne rozwiązanie, które sprawia, że kod jest bardziej czytelny i zrozumiały.
     - JSX jest następnie transpilowany do zwykłego kodu JavaScript przy użyciu narzędzi takich jak Babel.
  
3. Virtual DOM:
     - React korzysta z wirtualnego DOM (Virtual DOM) do efektywnego zarządzania zmianami w interfejsie użytkownika. Zamiast bezpośrednio manipulować rzeczywistym DOM, React najpierw tworzy jego wirtualną kopię.
     - Kiedy stan aplikacji się zmienia, React aktualizuje Virtual DOM, a następnie oblicza minimalny zestaw zmian, które trzeba wprowadzić do rzeczywistego DOM, aby zsynchronizować go z Virtual DOM. Ta optymalizacja sprawia, że operacje na DOM są szybsze i bardziej wydajne.

4. Jednokierunkowy przepływ danych (One-way Data Binding):
     - W React dane przepływają w jednym kierunku, z komponentu nadrzędnego do podrzędnego za pomocą propsów. Ułatwia to śledzenie, skąd pochodzą dane i jak są używane, co jest pomocne w debugowaniu i utrzymaniu kodu.

5. Stan (State) i Życie Komponentu:
     - Każdy komponent może mieć swój wewnętrzny stan, który przechowuje informacje o bieżącym stanie komponentu. Kiedy stan się zmienia, komponent automatycznie renderuje się ponownie, aby odzwierciedlić te zmiany.
     - Komponenty mają również cykl życia, który obejmuje fazy takie jak montowanie, aktualizowanie i odmontowywanie, co pozwala na wykonywanie określonych operacji w odpowiednich momentach.

## Ekosystem Reacta

React jest często używany razem z innymi bibliotekami i narzędziami, które tworzą cały ekosystem wspierający budowę złożonych aplikacji:
- Redux lub Context API: Biblioteki do zarządzania stanem globalnym w aplikacji.
- React Router: Biblioteka do zarządzania routingiem w aplikacjach jednostronicowych.
- Next.js: Framework do budowania aplikacji React z funkcjonalnościami takimi jak rendering po stronie serwera i generowanie statycznych stron.
- Create React App: Narzędzie do szybkiego tworzenia nowej aplikacji React z minimalną konfiguracją.

























