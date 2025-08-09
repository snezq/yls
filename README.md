幼儿罗智莹小视频weyvv国产的suv视频

ushort address = 5;
ushort value = 123;
master.WriteSingleRegister(1, address, value);
ushort inputStartAddress = 0;
ushort numInputRegisters = 5;
ushort[] inputRegisters = master.ReadInputRegisters(1, inputStartAddress, numInputRegisters);
foreach (var inputRegister in inputRegisters)
{
    Console.WriteLine(inputRegister);
}ushort address = 5;
ushort value = 123;
master.WriteSingleRegister(1, address, value);
