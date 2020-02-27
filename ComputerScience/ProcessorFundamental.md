# Processor Fundamentals

## Buses
> Exam:
> - 直接填写 `bus width`, `clock speed` 等作用和对性能的影响
> - 直接填写各 `bus` 的作用
> - 看表格填写各 `bus` 间的联系

- `Address bus`: transmits an address between the processor and memory. **(One way)**
- `Data bus`: sends data between the processor, memory and input-output devices. (Two way)
- `Control Bus`: signals sent by processor to control the memory and peripheral devices. (Two way)

`Bus width`: determines maximum possible memory capacity of the system

`Clock speed`: (MHz/GHz) the number of cycles that are performed by the CPU per second.

> Faster clock speed means processes of fetch, decode and execute occur faster however faster clock speed causes processor to heat up

`Clock tick` = `Clock cycle`

`Clock rate:` (MHz/GHz) the speed at which a micro-processor execute instructions

## Registers

| Abbr. | Full Name                    | Function                                                                                                          |
|:------|:-----------------------------|:------------------------------------------------------------------------------------------------------------------|
| MAR   | Memory address register      | stores the address of location for read/write operation                                                           |
| MDR   | Memory data register         | stores the data involved in read/write operation                                                                  |
| PC    | Program counter              | contains the location of the instruction that is to be executed next.                                             |
| ACC   | Accumulator                  | (single general-purpose register) stores the result of arithmetic and logic operations performed by the processor |
| CIR   | Current instruction register | holds the instruction that is to be executed                                                                      |

![](.ProcessorFundamental_images/3715043a.png)

#### How to read content

1. MAR -> address
2. Read signal is sent by processor to memory
3. content -> MDR

#### How to write content

1. content -> MDR
2. address -> MAR
3. Write signal sent by processor to memory
4. Content is changed