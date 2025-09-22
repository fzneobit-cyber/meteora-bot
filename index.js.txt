require('dotenv').config();

console.log("Meteora bot started...");

// Per ora fa solo “heartbeat”, ogni minuto stampa un log.
// Dopo possiamo aggiungere connessione RPC, pool Meteora ecc.
setInterval(() => {
  console.log("Bot still alive at", new Date().toISOString());
}, 60000);
