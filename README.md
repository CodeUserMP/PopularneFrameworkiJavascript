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

## Narzędzia użyte w projekcie:

MUI - to popularna biblioteka komponentów do React, która implementuje zasady projektowania Material Design opracowane przez Google. MUI ułatwia tworzenie nowoczesnych, responsywnych i estetycznych interfejsów użytkownika, oferując szeroki zestaw gotowych komponentów, które można łatwo dostosować do własnych potrzeb.

### Główne cechy MUI:

1. Implementacja Material Design:
   - MUI dostarcza zestaw komponentów zgodnych ze standardami Material Design, co pozwala na tworzenie spójnych i estetycznych interfejsów użytkownika.
   - Komponenty te obejmują przyciski, pola tekstowe, dialogi, menu, nawigację i wiele innych.
  
2. Responsywność:
   - MUI zawiera system siatki (Grid System) oraz inne narzędzia ułatwiające tworzenie responsywnych układów, które dobrze wyglądają na różnych urządzeniach i rozdzielczościach.
  
3. Dostosowywanie i stylizacja:
   - MUI oferuje rozbudowane możliwości dostosowywania, dzięki którym można modyfikować wygląd komponentów za pomocą różnych technik, takich jak API do stylizacji (styled-components, @emotion), motywy (themes) oraz makeStyles i withStyles.
   - Możliwość tworzenia własnych tematów (themes) pozwala na globalne zarządzanie kolorami, typografią i innymi aspektami wyglądu aplikacji.
  
4. Obszerna dokumentacja i społeczność:
   - MUI posiada obszerną dokumentację, która zawiera przykłady użycia komponentów, poradniki i API reference.
   - Aktywna społeczność użytkowników oraz regularne aktualizacje zapewniają, że MUI jest stale rozwijane i wspierane.
  
### Podstawowe komponenty MUI

MUI oferuje szeroki zestaw komponentów, które można łatwo zaimportować i użyć w aplikacji React. Oto kilka przykładów:
- Button: Komponent przycisku, który można łatwo dostosować.
- TextField: Komponent pola tekstowego z obsługą walidacji.
- AppBar: Komponent paska aplikacji, często używany do nawigacji.
- Drawer: Komponent szuflady nawigacyjnej.
- Card: Komponent karty, który można używać do wyświetlania zgrupowanych informacji.

## React Hooks

React Hooks to funkcje, które pozwalają korzystać z funkcji React, takich jak stan i cykl życia komponentu, w komponentach funkcyjnych. Wcześniej te funkcje były dostępne tylko w komponentach klasowych, ale od wersji React 16.8 są dostępne również w komponentach funkcyjnych dzięki Hooks.

### Najważniejsze Hooks

1. useState - Służy do dodawania stanu lokalnego do komponentu funkcyjnego. Zwraca parę: bieżący stan i funkcję do jego aktualizacji.
2. useEffect - Służy do zarządzania efektami ubocznymi w komponentach, takich jak pobieranie danych, subskrypcje czy ręczne manipulacje DOM. Działa podobnie do metod cyklu życia komponentów klasowych componentDidMount, componentDidUpdate i componentWillUnmount.
3. useContext - Służy do korzystania z kontekstu (context) w komponentach funkcyjnych. Pozwala na dostęp do wartości kontekstu bez konieczności korzystania z komponentu wyższego rzędu (HOC).
4. useReducer - Alternatywa dla useState, idealna do zarządzania bardziej złożonym stanem w komponentach. Działa podobnie do reduktora w Redux.
5. useRef - Służy do tworzenia referencji do elementów DOM lub do przechowywania wartości, która nie wymusza ponownego renderowania komponentu.

### Przechowywanie stanu aplikacji

Zarządzanie stanem jest kluczowym aspektem budowania dynamicznych aplikacji. React oferuje kilka sposobów przechowywania i zarządzania stanem:

1. Stan lokalny (useState):
   - Przechowuje stan lokalny w pojedynczym komponencie.
   - Jest idealny do prostych przypadków użycia, gdzie stan nie musi być współdzielony między komponentami.
  
2. Stan globalny (Context API):
   - Pozwala na tworzenie globalnych stanów, które mogą być dostępne dla dowolnego komponentu w drzewie komponentów.
   - Idealny do przekazywania danych na różnych poziomach hierarchii komponentów bez konieczności przekazywania propsów.

3. Zaawansowane zarządzanie stanem (useReducer):
   - Używane do bardziej złożonych przypadków, gdzie stan ma wiele wartości lub gdy wymagane jest bardziej złożone zarządzanie logiką stanu.
   - Można go porównać do reduktora w Redux.

4. Zewnętrzne biblioteki (Redux, MobX, Recoil):
   - W przypadku bardzo dużych aplikacji, gdzie zarządzanie stanem jest kluczowe, można użyć zewnętrznych bibliotek takich jak Redux, MobX czy Recoil.
   - Te biblioteki oferują zaawansowane narzędzia do zarządzania stanem, middleware, synchronizację stanu z lokalnym magazynem itp.























