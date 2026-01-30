  <h2>GCP- Componente Data Mapping</h2>
  <p> O projeto consiste em uma automacao que recebe uma informacao de texto (um nome) e a processa para gerar uma resposta automatica. </p>

  <h2>Processo</h2>
  <p>O fluxo e composto por dois passos:</p>
  <ul>
    <li><strong>Gatilho (API Trigger):</strong> E o ponto de partida que recebe os dados externos.</li>
    <li><strong>Mapeamento (Data Mapping):</strong> E onde a informacao e organizada para gerar o resultado final.</li>
  </ul>

  <h2>Informacoes Tecnicas</h2>
  <table border="1" width="100%" style="border-collapse: collapse;">
    <thead>
      <tr align="left" style="background-color: #f2f2f2;">
        <th style="padding: 10px;">Item</th>
        <th style="padding: 10px;">Descricao</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px;"><strong>Regiao</strong></td>
        <td style="padding: 10px;">southamerica-east1</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Entrada</strong></td>
        <td style="padding: 10px;">v_nome (Texto que voce envia)</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><strong>Saida</strong></td>
        <td style="padding: 10px;">v_resposta1 (Texto que voce recebe)</td>
      </tr>
  
    </tbody>
  </table>

  <br>

  <div style="background-color: #fafafa; padding: 20px; border: 1px solid #ddd;">
    <h2>Validação/Teste</h2>
    <ol>
      <li>Abra o editor da integracao no Google Cloud.</li>
      <li>Clique na opcao <strong>Test</strong> localizada no menu superior.</li>
      <li>No campo <strong>v_nome</strong>, digite o nome que deseja processar.</li>
      <li>Execute o teste e verifique o resultado exibido em <strong>v_resposta1</strong>.</li>
    </ol>
  </div>
  <hr>
