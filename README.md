# text-to-speech
## Conversor de texto para fala utilizando JavaScript puro.

Utilizado Web API **SpeechSynthesis**, interface controladora para o serviço de fala, herdada da interface pai, **EventTarget**.

A Propriedade: <br />
  **speechSynthesis.speaking** -> valor booleano que retorna true se algum utterance estiver em processo, mesmo se pausado.
  
Os métodos: <br /> 
  **.getVoices()** -> retorna uma lista de vozes disponíveis no dispositivo. <br />
  **.speak()** -> adiciona utterance à fila. Será falado quando outros utterances forem falados. <br />
  **.resume()** -> retorna em estado não pausado. <br />
  **.pause()** -> coloca em estado de pausa. <br />
  
