# XSS Lab

Mini laboratoire XSS réalisé sur OWASP Juice Shop.

## Technologies utilisées
- Kali Linux
- Docker
- OWASP Juice Shop

## Vulnérabilité
Cross-Site Scripting (XSS)

## Payload utilisé

```html
<iframe src="javascript:alert('XSS')">
Impact

Exécution de JavaScript
Modification du contenu HTML
Phishing
Vol de session
Mitigation
Validation des entrées
CSP
Cookies HTTPOnly
Encodage HTML
## Captures d’écran

### Payload XSS exécuté

![XSS](nom-de-ton-image.png)

### Modification du contenu HTML

![Hacked](nom-de-ton-image2.png)

### Docker actif

![Docker](nom-de-ton-image3.png)
