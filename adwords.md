

### Tag globale del sito
```javascript
<!-- Global site tag (gtag.js) - Google Ads: 759572556 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=AW-759572556"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'AW-759572556');
</script>
```

### Order Service - Snippet evento.
```js
<!-- Event snippet for order service conversion page
In your html page, add the snippet and call gtag_report_conversion when someone clicks on the chosen link or button. -->
<script>
function gtag_report_conversion(url) {
  var callback = function () {
    if (typeof(url) != 'undefined') {
      window.location = url;
    }
  };
  gtag('event', 'conversion', {
      'send_to': 'AW-759572556/EXySCOKw368BEMzQmOoC',
      'value': 10.0,
      'currency': 'USD',
      'transaction_id': '',
      'event_callback': callback
  });
  return false;
}
</script>


```