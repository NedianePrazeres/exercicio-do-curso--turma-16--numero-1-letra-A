# exercicio-do-curso-turma-16-numero-1-letra-A
letra A do exercicio 1 do curso- grupo 16


function addIsAdult(person) {
  return {
    ...person,
    isAdult: person.age >= 18
  };
}

// Exemplo de uso:
const pessoa = { name: "Ana", age: 22 };
const novaPessoa = addIsAdult(pessoa);
console.log(novaPessoa);
// Saída: { name: "Ana", age: 22, isAdult: true }
