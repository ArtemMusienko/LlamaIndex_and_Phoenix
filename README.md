![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## LlamaIndex and Phoenix

В этом репозитории представлена *RAG-система*, которая обучается по *PDF-книге,* предварительно загруженной на **Google Диск**. За основу взят **LlamaIndex**. В качестве просмотра трассировок используется инструмент **Phoenix**. Для получения его *UI-версии* я использовал защищенный туннель от **Cloudflared**.

В коде реализован *API-ключ,* который получен от сервиса **VseGPT**, поэтому настройка отличается от стандартной. Мне необходимо задействовать **base_url**, что является особенностью использования этого ключа.

> Рекомендую использовать этот код в **Google Colab** и задействовать
> **графический ускоритель T4**!
