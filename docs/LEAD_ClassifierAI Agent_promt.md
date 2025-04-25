We have a new inbound lead and we need you to classify it into either SaaS or development agency category.

Here is the lead information:

**Name:** {{ $json['Lead Name'] }}

**Request:** {{ $json.Message }}

**Company Information:** 
{{ $json['Company Information'] }}

If the lead a SaaS company, output 'SaaS'
If the lead is a development agency, output 'Agency'