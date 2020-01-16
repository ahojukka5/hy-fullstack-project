# Projektin kuvaus

Projektin tavoitteena on tehdä web-sovellus, jonka avulla voi suunnitella
matkustamista. Vähimmäisvaatimuksena on toteuttaa toiminnallisuus, jolla
käyttäjä voi laskea erilaisten päivämäärien välisiä ajallisia etäisyyksiä,
esimerkiksi:

- countdown johonkin tiettyyn päivämäärään
- kahden annetun päivämäärän välinen etäisyys
- useamman annetun päivämäärän välisiä etäisyyksiä

## (Mahdollisia) ominaisuuksia:

- mahdollisuus asentaa kännykälle PWA-applikaatioksi
- responsiivinen ui ja sujuva kännykällä käyttö
- multilanguage
- OAuth-kirjautuminen
- paikkojen ja reittien tallentamista, säätietoja, muuta metatietoa, kuten
  hotellivarauksia, matka-aikatauluja yms.
- Google-kalenteriin integrointi
- laajentaminen travel planning appsiksi, jossa voi porukalla tehdä
  ja jakaa matkustussuunnitelmia

## Tekninen toteutus

- frontend tehdään React.js ( + Gatsby.js? )
- backendinä toimii Firebase / Parse
- hostaus Netlify / Firebase
- serverless JAMstack -periaatteella
- projektin lähdekoodi GitHubissa
- automaattinen testaus Travis-CI:llä
- dokumentointi Storybook ja/tai React Styleguidist
- linttaus Eslint, code formatting Prettier
- testaus Cypress ja Jest
- käyttöliittymäsuunnittelu Codepen
- IDE VSCode, StackBlitz?
- tyylit Emotion.js / styled-components / Material-UI
- Docker-konttien käyttö?
- raportointi / dokumentointi Markdown + Gatsby?

Deployment, testaus, dokumentoinnin generointi ja muu vastaava pitää tapahtua
automaattisesti ja triggeröityä kun repositoryyn pushataan uusi commit.
