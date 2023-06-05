# Coinlist registration 

# Run from dashboard CoinList
```javascript
document.getElementsByClassName('c-button c-button--small c-button--gray js-notification_link js-analytic_track_link market-dashboard-notifications-notification_row__primary_link')[0].click();
```

# Run from sale page
```javascript
document.getElementsByClassName('c-button c-button--large cta-button register-buttons')[0].click();
```

```javascript
document.getElementsByClassName('c-button c-button--large js-get_started_cta ht')[0].click();
```

```javascript
document.getElementsByClassName('c-button c-button--large s-paddingHoriz4 js-submit_existing_entity')[0].click();
```

```javascript
document.getElementsByClassName('c-label c-label c-label--inline')[0].click(); // check confirm residence checkbox
  let element = document.getElementById('forms_offerings_participants_residence_residence_country');
  element.value = 'RU';
document.getElementsByClassName('js-submit c-button c-button--large ht')[0].click();
```

```javascript
let run=async()=>{let e=document.body.querySelectorAll(".quiz")[0].querySelectorAll(".c-label--inline"),t=e=>new Promise(t=>setTimeout(t,e)),a=["50,000,000","Users in the waiting room for the sale will be given a random spot in the queue when the sale starts. Users who arrive after the sale starts for the sale will be placed behind those in the waiting room","Neon is an EVM that allows Ethereum dApps to function within Solana","USDC, USDT","$0.10 per token, $500 max purchase amount","The user's purchase may be canceled and the user may be banned from future CoinList sales","CoinList.co","The user's account will be terminated and all purchases will be canceled"];for(let l=0;l<e.length;l++)-1!==a.indexOf(e[l].textContent)&&(e[l].querySelectorAll(".c-input")[0].checked=!0);await t(200),document.body.querySelector(".js-submit").click()};run();
```

# If need click "No Thanks" on page with linked wallet
```javascript
document.getElementsByClassName('c-button c-button--secondary c-button--small s-marginRight1')[0].click();
```
