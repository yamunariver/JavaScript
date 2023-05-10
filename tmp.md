

let x = 1212121

``const exp = `${x}` // 1212121``
``const split = `${x}`.split() //['1212121']``
``const split = `${x}`.split('') //['1','2','1','2','2','1']``
``const split = `${x}`.split('').reverse()   //[ '1', '1', '2', '1' ]``
``const split = `${x}`.split('').reverse('') //[ '1', '1', '2', '1' ]``
``const split = `${x}`.split('').reverse('').join() //1,1,2,1``
``const split = `${x}`.split('').reverse('').join('') //1121``
