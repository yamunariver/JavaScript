const obj1 = {
	name: 'hello'
}

const obj2 = {
	city: 'hyderabad',
}

## old

const res = Object.assign({}, obj1, obj2)

console.log(res	)

## new

const obj1 = {
	name: 'hello'
}

const obj2 = {
	city: 'hyderabad',
  ...obj1
}

console.log(obj2)


if we obj1 or obj2 in the top of the object

console.log(...obj1, ...obj2)
