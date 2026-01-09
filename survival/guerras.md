---
authors:
  - fpalomo
categories:
  - survival
  - guerras
---
# Atacar a un enemigo
Para atacar a un enemigo, simplemente necesitas colocar un bloque específico (por defecto, una **OAK_FENCE**) en una parcela de una ciudad enemiga donde se cumplan las condiciones adecuadas. Si el ataque tiene éxito, se generará una **bandera de guerra** y aparecerá un **War Beacon** en el cielo, justo encima del centro de la parcela.

## Condiciones habituales para iniciar un ataque con bandera
- En tu archivo `flagwar config.yml` debe estar configurado `allow_attacks: true`.
- No debes ser **OP** del servidor.
- Debes estar en un mundo donde la guerra esté permitida.
  - El comando `/townyworld` te indicará si la guerra está activada en el mundo en el que te encuentras.
  - Usa `/tw toggle warallowed` para cambiar esta propiedad del mundo.
- Debes colocar la bandera en un lugar donde no haya ningún techo por encima.  
  *(Debe haber cielo abierto.)*
- Tanto tu ciudad como la ciudad enemiga deben pertenecer a una nación, y esas naciones deben considerarse enemigas entre sí.
- Ni tú ni la ciudad enemiga debéis estar en modo neutral o pacífico.
- Es posible que tú y los defensores tengáis que cumplir un número mínimo de jugadores conectados en la ciudad y/o nación.
- Puede que tengas que atacar primero las parcelas del borde de la ciudad antes de avanzar hacia el interior.
- Puede que tengas que pagar dinero para colocar la bandera.

Cada **bandera de guerra** tiene varias fases, y tanto la bandera como el beacon cambian de material en cada fase. Cuando la fase final expira sin que la bandera haya sido destruida, la parcela atacada pasa a ser tuya y la bandera desaparece.

Por defecto, los jugadores solo pueden iniciar un único ataque a la vez hasta que su bandera sea destruida.

Para proteger la bandera de los defensores, puedes optar por construir alrededor de ella, aunque esto puede o no estar permitido según las normas del servidor en el que juegues. La mejor forma de proteger la bandera es mantener a los defensores alejados mediante el combate.

---
# Defender un ataque

Para defender una parcela bajo ataque, tienes tres objetivos principales:

1. **Destruir la bandera**
2. **Repeler a los atacantes**
3. **Asegurar la zona**

La forma de conseguirlo depende de ti. Por defecto, las banderas están hechas de **lana** con una **valla de madera** como base. Por ello, usar un **hacha** o **tijeras** será más efectivo que una espada. Aun así, mantén tu espada a mano, ya que probablemente habrá atacantes cerca con ganas de luchar.
---
