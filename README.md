# Code

=> npx ts-jest config:init

=> create file jest.config.js

=> teste unitário
=> teste de integração

- it or test => o uso do it a descrição fica conciso
- Asserções Aspecto modal de uma declaração, positiva ou negativa
- toBe() => valores simples
- toEqual() => objects
- SUT
  sut(System under test) => classe a ser testada

=> Checar comportamento

- jest.spyOn
- jest.spyOn(console, 'log'); // objeto segundo parâmetro método

- afterEach(() => jest.clearAllMocks());
- depois de cada teste limpar os mocks example .spyOn
