# test2

{
  "type": "script",
  "seleniumVersion": "2",
  "formatVersion": 2,
  "steps": [
    {
      "type": "get",
      "url": "https://www.walmart.com.br/"
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "link text",
        "value": "Notebooks"
      }
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "link text",
        "value": "Notebook Samsung Intel Dual Core 2GB 16GB Chromebook 11.6’’ Google Chrome OS   11"
      }
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "link text",
        "value": "+"
      }
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "xpath",
        "value": "//section[@id='buybox-Walmart']//button[.='Adicionar ao carrinho']"
      }
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "id",
        "value": "navegaCarrinho"
      }
    },
    {
      "type": "clickElement",
      "locator": {
        "type": "link text",
        "value": "Notebook Samsung Intel Dual Core 2GB 16GB Chromebook 11.6’’ Google Chrome OS - Chromebook Samsung Intel Celeron N3050 2 GB 16 GB XE500C13-AD1BR 11.6’’ Google Chrome OS"
      }
    }
  ],
  "data": {
    "configs": {},
    "source": "none"
  },
  "inputs": [],
  "timeoutSeconds": 60
}
