##���� [coffee_machine_v.1.2.cpp](https://github.com/igotbitches/coffee_machine/blob/mikalai/coffee_machine_v.1.2.cpp)


<ol type="a">
<li>����� ������� <i>Main Menu</i> �� ������� <code>mainMenu()</code> ����� ����� ��������, ���� ���������� ������. ������ ������� ���������� ������. ������ �� ������� � ��������� ����.</li>

```c++
cout << "\t\t\tMain Menu" << endl;
cout << endl;
```

<li>������������ ���������� � <code>#define</code> (����� ����� �������� �����������,
������������ ������ ������ �� ��������� ����)</li>

```c++
#define TEN_COINS 0.1
#define TWENTY_COINS 0.2
#define FIFTY_COINS 0.5
#define ONE_RUB 1
#define TWO_RUB 2
```

<li>������� <code>int customerChoose(int &choose)</code> ������ <b>void</b> 
(�� �������� ���� �������� �� ������, ��� � ����� ������ ��������, 
���� ���� �� ��� �� ����������) � ������������ � <code>choiceMenu()</code>, 
�.�. � ��� ��� ��������� �������, �� ����</li>

```c++
void choiceMenu(int &choose);
```

<li>����� � �������� <code>serviceMenu()</code> � <code>mainMenu()</code> �������� ����������
�� ������. �� ��� �� ��������, ��� � ����. � ���� �������� ��� �� ����� ������ ����������.</li>

<li>�� ��������� ������ ���������� ��� <code>goto</code>. ����� �������, 
�� ����������� ��� ��� ��� �� ���������, � ������, ��� ��������� � ���� ���� �������, 
������� ���������� �� �� ������������. ����������� ���, �������, 
����� ����� ���� ������� ��������� ������ ����.</li>

<li>��� ����� ����� �� �� 1 �� 5 ��������� <em><b>��������</b></em> � ������ �� ���������� mainMenu()</li>

```text
���� ����� ���������. ������ ��������� ����������� ��������� ��� goto.
goto ������ ������ ��� ��������������� � ������. �� �������.
```





</ol>


