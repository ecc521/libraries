# JavaScript Function Libraries

These libraries are not actively maintained. You're welcome to use them (and the code should still be accurate, since RSA hasn't really changed since it was invented), but I make no guarantees as to accuracy. 

## About the Libraries

### random.js
- High performance cryptographically secure random number generation
- Uses crypto.getRandomValues()
- Always returns a BigInt
- Does not throw if min > max

Call using lib.random(min, max)


### indexeddb.js
- localStorage in indexedDB


## The following are currently undergoing major changes

#### rsa.js
rsa.js is a function library for anything related to RSA. Examples include:
- Modular Exponentation
- Miller-Rabin Test
- Fermat Test
- Trial Factoring
- Modular Inverse (Not added Yet)
- Safe Prime Tester (Not added Yet)
- Strong Prime Tester (Not added Yet)
- RSA Prime Generator (Not added Yet)

All rsa.js functions return BigInt's if applicable