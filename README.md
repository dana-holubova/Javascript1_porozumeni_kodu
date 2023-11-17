# Javascript1_porozumeni_kodu

*Vyzkoušejte si, jak dobře umíte číst JavaScriptový kód.*

Přečtěte si následující úryvky kódu a u každého řekněte, co program vypíše do stránky aniž byste program spouštěli.

**Úryvek 1:**

```
const name = 'Mississippi';

if (name.length > 5) {
  const name = 'Missi';
  document.body.innerHTML += `<p>${name}</p>`;
}

document.body.innerHTML += `<p>${name}</p>`;
```

**Úryvek 2:**

```
const name = 'Franta';

const greet = (name) => {
  const name = 'Pepa';
  document.body.innerHTML += `<p>${name}</p>`;
};

greet('Jožin');
```

**Úryvek 3:**

```
const age = 25;

if (age > 21) {
  const price = 100;
} else if (age > 15) {
  const price = 50;
} else {
  const price = 0;
}

document.body.innerHTML += `<p>${price}</p>`;
```


