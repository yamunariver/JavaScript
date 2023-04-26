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


if ...obj1 or ...obj2 in the top of the obj1 or obj2

const obj1 = {
	name: 'world',
const obj2 = {
	...obj1,
	name: 'hello'
	## if parameter names are similar in the obj1 and obj2 that are parameters are merged

console.log(obj2)  ## hello

## and 

const obj1 = {
	name: 'world',
const obj2 = {
	name: 'hello',
	..obj1
	## if parameter names are similar in the obj1 and obj2 that are parameters are merged

console.log(obj2)  ## world



console.log(...obj1, ...obj2)
