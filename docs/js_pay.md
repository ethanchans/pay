# ����JSSDK֧��

## URL
   * ���Ի���: http://qa.maxfun.co/qrcode?m=
   * ��ʽ����:
   
## Request
```
{
    "tp_trade_no": "1271TP1487057748363124",
    "mch_key": "378284f3-31d4-4d75-8c3a-0c540ee67034",
    "total_fee": 0.01,
	"nonce_str":"zcmxk"
}

���������json������Base64���ܣ��ŵ�m=������תurl
����:
��{"tp_trade_no":"1271TP1487057748363124","mch_key":"378284f3-31d4-4d75-8c3a-0c540ee67034","total_fee":0.01,"nonce_str":"zcmxk"}
����Base64�õ��ļ��ܴ�Ϊ:
eyJ0cF90cmFkZV9ubyI6IjEyNzFUUDE0ODcwNTc3NDgzNjMxMjQiLCJtY2hfa2V5IjoiMzc4Mjg0ZjMtMzFkNC00ZDc1LThjM2EtMGM1NDBlZTY3MDM0I
iwidG90YWxfZmVlIjowLjAxLCJub25jZV9zdHIiOiJ6Y214ayJ9
�Ѽ��ܴ��ŵ�m=����,
��m=eyJ0cF90cmFkZV9ubyI6IjEyNzFUUDE0ODcwNTc3NDgzNjMxMjQiLCJtY2hfa2V5IjoiMzc4Mjg0ZjMtMzFkNC00ZDc1LThjM2EtMGM1NDBlZTY3MDM0IiwidG90YWxfZ
mVlIjowLjAxLCJub25jZV9zdHIiOiJ6Y214ayJ9
��תurl:
http://qa.maxfun.co/qrcode?m=eyJ0cF90cmFkZV9ubyI6IjEyNzFUUDE0ODcwNTc3NDgzNjMxMjQiLCJtY2hfa2V5IjoiMzc4Mjg0ZjMtMzFkNC00ZDc
1LThjM2EtMGM1NDBlZTY3MDM0IiwidG90YWxfZmVlIjowLjAxLCJub25jZV9zdHIiOiJ6Y214ayJ9

```
����˵����

<table data-tablesaw-sortable>
    <thead>
        <tr>
            <th data-tablesaw-sortable-col data-tablesaw-sortable-default-col>�ֶ�����</th>
            <th data-tablesaw-sortable-col>����</th>
            <th data-tablesaw-sortable-col>����</th>
            <th data-tablesaw-sortable-col>�Ƿ����</th>
        </tr>
		<tr>
            <td>mch_key</th>
            <td>�ַ���</th>
            <td>�̻���ʶ��</th>
            <td>��</th>
        </tr>
		<tr>
			<td>total_fee</th>
			<td>����(Double)</th>
			<td>���׽��</th>
			<td>��</th>
		</tr>
		<tr>
            <td>tp_trade_no</th>
            <td>�ַ���</th>
            <td>�̻�������</th>
            <td>��</th>
        </tr>
		<tr>
            <td>nonce_str</th>
            <td>�ַ���</th>
            <td>����ַ���(����ÿ��������������ɵ�)</th>
            <td>��</th>
        </tr>
    </thead>
<table>

## JSSDK֧�����֪ͨ
* [JSSDK֧�����֪ͨ˵���ĵ�](https://github.com/maxfunapi/pay/blob/master/docs/async_notify.md)
