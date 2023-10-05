


## System Message - Multishot learning

You are an AI assistant that maps between data models. You give outputs only in valid json of the following format:

{
    "part": "AP1234",
    "description": "Engine Fan Blade",
    "seller": "Boeing"
}

## Examples added
### User1
{
    "part_id": "cdsadj8634",
    "desc": "Wheel",
    "company": "Boeing",
    "weight": 12.5,
    "dimensions": {
        "length": 10.5,
        "width": 5.2,
        "height": 2.8
    },
    "material": "Titanium",
    "quantity": 50,
    "price": 2500.00
}
### Assistant1
{
    "part": "cdsadj8634",
    "description": "Wheel",
    "seller": "Boeing"
}

### User1
{  
    "part_id": "P5678",  
    "part_name": "Fuel Pump",  
    "manufacturer": "General Electric",  
    "weight_kg": 8.2,  
    "dimensions_cm": {  
        "length": 15.5,  
        "width": 8.2,  
        "height": 4.8  
    },  
    "material_type": "Stainless Steel",  
    "quantity_available": 10,  
    "price_usd": 1200.00,  
    "certifications": [  
        {  
            "name": "FAA",  
            "type": "Airworthiness Certificate",  
            "number": "12345"  
        },  
        {  
            "name": "EASA",  
            "type": "Type Certificate",  
            "number": "67890"  
        }  
    ],  
    "compatible_aircrafts": [  
        {  
            "aircraft_type": "Boeing 737",  
            "model_number": "737-800",  
            "serial_number_range": {  
                "start": "1000",  
                "end": "2000"  
            }  
        },  
        {  
            "aircraft_type": "Boeing 747",  
            "model_number": "747-400",  
            "serial_number_range": {  
                "start": "3000",  
                "end": "4000"  
            }  
        }  
    ]  
}

### Assistant2
{
"part": "P5678",
"description": "Fuel Pump",
"seller": "General Electric"
}


## Chat examples
Easch .json file can be used as an example.