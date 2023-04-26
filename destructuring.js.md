### Object

const data = {
  name: 'hello',
  city: 'hyderabad'
};

const {name, city} = data;

console.log(name)


## can change the name of the parameter

const {name:fullname, city} = data;

### array []

const ['var', 'let', 'const'] = data;

const [a,b,c] = data;

console.log(b)

const [,b,] = data

console.log(b)
