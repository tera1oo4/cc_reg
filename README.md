# cc_reg
CyberConnect Coinlist registration 
```javascript
document.getElementsByClassName('c-button c-button--small c-button--gray js-notification_link js-analytic_track_link market-dashboard-notifications-notification_row__primary_link')[0].click();

document.getElementsByClassName('c-button c-button--large cta-button register-buttons')[0].click();

document.getElementsByClassName('c-button c-button--large js-get_started_cta ht')[0].click();

document.getElementsByClassName('c-button c-button--large s-paddingHoriz4 js-submit_existing_entity')[0].click();


document.getElementsByClassName('c-label c-label c-label--inline')[0].click(); // check confirm residence checkbox
  let element = document.getElementById('forms_offerings_participants_residence_residence_country');
  element.value = 'RU';
document.getElementsByClassName('js-submit c-button c-button--large ht')[0].click();

let run=async()=>{let e=document.body.querySelectorAll(".quiz")[0].querySelectorAll(".c-label--inline"),t=e=>new Promise(t=>setTimeout(t,e)),n=["3,000,000","Users in the waiting room for the sale will be given a random spot in the queue when the sale starts. Users who arrive after the sale starts for the sale will be placed behind those in the waiting room.","CyberConnect is a decentralized social network that allows users to own their digital identity, content, connections, and monetization channels","USDC, USDT","$1.80 per token, maximum purchase of $500","The user's purchase may be canceled and the user may be banned from future CoinList sales","CoinList.co","The user's account will be terminated and all purchases will be canceled"];for(let a=0;a<e.length;a++)-1!==n.indexOf(e[a].textContent)&&(e[a].querySelectorAll(".c-input")[0].checked=!0);await t(200),document.body.querySelector(".js-submit").click()};run();```
