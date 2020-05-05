<p><strong><u>Project Workout:</u></strong></p>
<p>Project: 15-bit single cycle cpu.</p>
<p>Group members:</p>
<table>
<tbody>
<tr>
<td>
<p>Ifran Rahman Nijhum</p>
</td>
</tr>
<tr>
<td>
<p>Mohammad Moshfique Uddin</p>
</td>
</tr>
</tbody>
</table>
<p><strong><u>Instructions</u></strong>: load, store, addition, substraction, multiplication, xor, beq.</p>
<p><strong><u>R-Type Instruction:</u></strong></p>
<table width="623">
<tbody>
<tr>
<td width="140">
<p>Opcode (3 bit)</p>
</td>
<td width="133">
<p>rs (3 bit)</p>
</td>
<td width="134">
<p>rt (3 bit)</p>
</td>
<td width="111">
<p>&nbsp;rd (3 bit)</p>
</td>
<td width="106">
<p>funct (3 bit)</p>
</td>
</tr>
</tbody>
</table>
<p>Instructions: addition, substraction, multiplication, division, xor.</p>
<table width="624">
<tbody>
<tr>
<td width="120">
<p>Instructions</p>
</td>
<td width="112">
<p>Hexadecimal</p>
<p>Instruction</p>
</td>
<td width="73">
<p>Opcode</p>
</td>
<td width="54">
<p>Rs</p>
</td>
<td width="48">
<p>Rt</p>
</td>
<td width="72">
<p>Rd</p>
</td>
<td width="144">
<p>Function</p>
</td>
</tr>
<tr>
<td width="120">
<p>Add</p>
</td>
<td width="112">
<p>04a0</p>
</td>
<td width="73">
<p>000</p>
</td>
<td width="54">
<p>010</p>
</td>
<td width="48">
<p>010</p>
</td>
<td width="72">
<p>100</p>
</td>
<td width="144">
<p>000</p>
</td>
</tr>
<tr>
<td width="120">
<p>Substract</p>
</td>
<td width="112">
<p>0891</p>
</td>
<td width="73">
<p>000</p>
</td>
<td width="54">
<p>100</p>
</td>
<td width="48">
<p>010</p>
</td>
<td width="72">
<p>010</p>
</td>
<td width="144">
<p>001</p>
</td>
</tr>
<tr>
<td width="120">
<p>Multiplication</p>
</td>
<td width="112">
<p>04a2</p>
</td>
<td width="73">
<p>000</p>
</td>
<td width="54">
<p>010</p>
</td>
<td width="48">
<p>010</p>
</td>
<td width="72">
<p>100</p>
</td>
<td width="144">
<p>010</p>
</td>
</tr>
<tr>
<td width="120">
<p>Xor</p>
</td>
<td width="112">
<p>0653</p>
</td>
<td width="73">
<p>000</p>
</td>
<td width="54">
<p>011</p>
</td>
<td width="48">
<p>001</p>
</td>
<td width="72">
<p>010</p>
</td>
<td width="144">
<p>011</p>
</td>
</tr>
</tbody>
</table>
<p><strong><u>I-Type Instruction:</u></strong></p>
<table>
<tbody>
<tr>
<td width="156">
<p>Opcode (3 bit)</p>
</td>
<td width="156">
<p>rs (3 bit)</p>
</td>
<td width="156">
<p>rt (3 bit)</p>
</td>
<td width="156">
<p>Immediate (6 bit)</p>
</td>
</tr>
</tbody>
</table>
<p>Instructions: load, store, beq</p>
<p>Rs, Rt, immediate values ar arbitrary.</p>
<table width="631">
<tbody>
<tr>
<td width="97">
<p>Instruction</p>
</td>
<td width="101">
<p>Hexadecimal</p>
<p>Instruction</p>
</td>
<td width="102">
<p>Opcode (3)</p>
</td>
<td width="102">
<p>Rs (3)</p>
</td>
<td width="121">
<p>Rt (3)</p>
</td>
<td width="108">
<p>Immediate (6)</p>
</td>
</tr>
<tr>
<td width="97">
<p>Load</p>
</td>
<td width="101">
<p>1283</p>
</td>
<td width="102">
<p>001</p>
</td>
<td width="102">
<p>001</p>
</td>
<td width="121">
<p>010</p>
</td>
<td width="108">
<p>000011</p>
</td>
</tr>
<tr>
<td width="97">
<p>Store</p>
</td>
<td width="101">
<p>2681</p>
</td>
<td width="102">
<p>010</p>
</td>
<td width="102">
<p>011</p>
</td>
<td width="121">
<p>010</p>
</td>
<td width="108">
<p>000001</p>
</td>
</tr>
<tr>
<td width="97">
<p>beq</p>
</td>
<td width="101">
<p>34c2</p>
</td>
<td width="102">
<p>011</p>
</td>
<td width="102">
<p>010</p>
</td>
<td width="121">
<p>011</p>
</td>
<td width="108">
<p>000010</p>
</td>
</tr>
</tbody>
</table>
<p><strong>15 Bit ALU: </strong></p>
<table>
<tbody>
<tr>
<td width="312">
<p>Instructions</p>
</td>
<td width="312">
<p>Alu Control</p>
</td>
</tr>
<tr>
<td width="312">
<p>Add</p>
</td>
<td width="312">
<p>00</p>
</td>
</tr>
<tr>
<td width="312">
<p>Sub</p>
</td>
<td width="312">
<p>01</p>
</td>
</tr>
<tr>
<td width="312">
<p>Mul</p>
</td>
<td width="312">
<p>10</p>
</td>
</tr>
<tr>
<td width="312">
<p>Xor</p>
</td>
<td width="312">
<p>11</p>
</td>
</tr>
</tbody>
</table>
<p><strong><u>ALU CONTROL</u></strong></p>
<table width="631">
<tbody>
<tr>
<td width="94">
<p>Instruction</p>
</td>
<td width="94">
<p>Instruction Operation</p>
</td>
<td width="69">
<p>AluOp1&nbsp;</p>
</td>
<td width="69">
<p>AluOp2</p>
</td>
<td width="51">
<p>Fun1</p>
</td>
<td width="51">
<p>Fun2</p>
</td>
<td width="51">
<p>Fun3</p>
</td>
<td width="76">
<p>ALU Control</p>
<p>Input1</p>
</td>
<td width="76">
<p>ALU Control</p>
<p>Input2</p>
</td>
</tr>
<tr>
<td width="94">
<p>LW</p>
</td>
<td width="94">
<p>Load word</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="76">
<p>0</p>
</td>
<td width="76">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p>SW</p>
</td>
<td width="94">
<p>Store word</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="51">
<p>X</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="76">
<p>0</p>
</td>
<td width="76">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p>Beq</p>
</td>
<td width="94">
<p>Branch eq</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="69">
<p>1</p>
</td>
<td width="51">
<p>X</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="51">
<p>x</p>
</td>
<td width="76">
<p>0</p>
</td>
<td width="76">
<p>1</p>
</td>
</tr>
<tr>
<td width="94">
<p>R-type</p>
</td>
<td width="94">
<p>Add</p>
</td>
<td width="69">
<p>1</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="76">
<p>0</p>
</td>
<td width="76">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p>R-type</p>
</td>
<td width="94">
<p>Sub</p>
</td>
<td width="69">
<p>1</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>1</p>
</td>
<td width="76">
<p>0</p>
</td>
<td width="76">
<p>1</p>
</td>
</tr>
<tr>
<td width="94">
<p>R-type</p>
</td>
<td width="94">
<p>Mul</p>
</td>
<td width="69">
<p>1</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>1</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="76">
<p>1</p>
</td>
<td width="76">
<p>0</p>
</td>
</tr>
<tr>
<td width="94">
<p>R-type</p>
</td>
<td width="94">
<p>xor</p>
</td>
<td width="69">
<p>1</p>
</td>
<td width="69">
<p>0</p>
</td>
<td width="51">
<p>0</p>
</td>
<td width="51">
<p>1</p>
</td>
<td width="51">
<p>1</p>
</td>
<td width="76">
<p>1</p>
</td>
<td width="76">
<p>1</p>
</td>
</tr>
</tbody>
</table>
<p><strong><u>CONTROL UNIT:</u></strong></p>
<table width="706">
<tbody>
<tr>
<td width="73">
<p>Instruction</p>
</td>
<td width="60">
<p>Opcode</p>
</td>
<td width="60">
<p>RegDst</p>
</td>
<td width="61">
<p>AluOp1</p>
</td>
<td width="61">
<p>AluOp2</p>
</td>
<td width="60">
<p>ALUSrc</p>
</td>
<td width="60">
<p>Branch</p>
</td>
<td width="70">
<p>MemRead</p>
</td>
<td width="74">
<p>MemWrite</p>
</td>
<td width="64">
<p>Regwrite</p>
</td>
<td width="61">
<p>Memto Reg</p>
</td>
</tr>
<tr>
<td width="73">
<p>R-format</p>
</td>
<td width="60">
<p>000</p>
</td>
<td width="60">
<p>1</p>
</td>
<td width="61">
<p>1</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="70">
<p>0</p>
</td>
<td width="74">
<p>0</p>
</td>
<td width="64">
<p>1</p>
</td>
<td width="61">
<p>0</p>
</td>
</tr>
<tr>
<td width="73">
<p>Lw</p>
</td>
<td width="60">
<p>001</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="60">
<p>1</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="70">
<p>1</p>
</td>
<td width="74">
<p>0</p>
</td>
<td width="64">
<p>1</p>
</td>
<td width="61">
<p>1</p>
</td>
</tr>
<tr>
<td width="73">
<p>Sw</p>
</td>
<td width="60">
<p>010</p>
</td>
<td width="60">
<p>X</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="60">
<p>1</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="70">
<p>0</p>
</td>
<td width="74">
<p>1</p>
</td>
<td width="64">
<p>0</p>
</td>
<td width="61">
<p>X</p>
</td>
</tr>
<tr>
<td width="73">
<p>beq</p>
</td>
<td width="60">
<p>011</p>
</td>
<td width="60">
<p>x</p>
</td>
<td width="61">
<p>0</p>
</td>
<td width="61">
<p>1</p>
</td>
<td width="60">
<p>0</p>
</td>
<td width="60">
<p>1</p>
</td>
<td width="70">
<p>0</p>
</td>
<td width="74">
<p>0</p>
</td>
<td width="64">
<p>0</p>
</td>
<td width="61">
<p>X</p>
</td>
</tr>
</tbody>
</table>
