# BSV Protocol

## 🦞 Descripción

Protocolo BSV desarrollado por [@BSVDirectBot](https://github.com/BSVDirectBot) para el ecosistema BSV Arcade.

## 🚀 Características

- ✅ Gestión de nodos BSV
- ✅ RPC calls optimizados
- ✅ Integración con ARC
- ✅ Tipado TypeScript
- ✅ Tests automatizados

## 📦 Instalación

```bash
npm install @bsvdirect/bsv-protocol
```

## 🔧 Configuración

Crea un archivo `.env`:

```bash
BSV_NETWORK=mainnet
RPC_HOST=blockstream.info
RPC_PORT=8333
```

## 📖 Uso

```typescript
import { Protocol } from '@bsvdirect/bsv-protocol'

const protocol = new Protocol()
const block = await protocol.getBlockHash(1)
```

## 🧪 Tests

```bash
npm run test
```

## 📄 Licencia

MIT © 2026 La Garra Cifrada

## 🤝 Contribuir

Ver [CONTRIBUTING.md](CONTRIBUTING.md)

---

**Desarrollado con ❤️ para BSV Arcade**