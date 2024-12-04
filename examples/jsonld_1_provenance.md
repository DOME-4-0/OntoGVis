# Example N 1 of Provenance Graph 

the row graph is in a separate file in this folder. below is a copy with annotation. 


- we need to be able to easilly see a user (usually with the iri:                     "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
`

For this we do not need to see the entire iri in MedusaVis, but merely something like "User_<last three letters>"
- Each user has a set of assciated activities, usually the user is the object, and the predicate is wasAssociatedWith linking to a subject, like so:\

`subject wasAssociatedWith user` 

we would like to see all users and anything they are the object of !

- We have activities such as LogIn, Transaction, etc (more info later).  

```jsonld
{
    "@graph": [
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_330fd4ed-c1bb-4acc-aa1f-32c8b2cc2f10",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:07:33.712728"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_330fd4ed-c1bb-4acc-aa1f-32c8b2cc2f10"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_330fd4ed-c1bb-4acc-aa1f-32c8b2cc2f10"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "that_liberty"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "330fd4ed-c1bb-4acc-aa1f-32c8b2cc2f10"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_98d651c5-cef6-4871-90a4-3a46442ec3a0",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:05:38.455240"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_98d651c5-cef6-4871-90a4-3a46442ec3a0"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_98d651c5-cef6-4871-90a4-3a46442ec3a0"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "eagle_minute"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "98d651c5-cef6-4871-90a4-3a46442ec3a0"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "carbon"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_dbe295e6-84b1-4b29-b879-bf083041ab11",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:07:46.252525"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_dbe295e6-84b1-4b29-b879-bf083041ab11"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_dbe295e6-84b1-4b29-b879-bf083041ab11"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "bright_rough"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "dbe295e6-84b1-4b29-b879-bf083041ab11"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_6fe1d0c4-0463-4db4-ad5a-d74153575650",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessDataSources"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:14:57.860016"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_6fe1d0c4-0463-4db4-ad5a-d74153575650"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_6fe1d0c4-0463-4db4-ad5a-d74153575650"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "hat_error"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "6fe1d0c4-0463-4db4-ad5a-d74153575650"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_969b06ab-442d-4ad7-8410-06ddee56e909",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessTools"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:24:38.357289"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_969b06ab-442d-4ad7-8410-06ddee56e909"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_969b06ab-442d-4ad7-8410-06ddee56e909"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "run_offer"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "969b06ab-442d-4ad7-8410-06ddee56e909"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_7c0533b8-d4ae-457a-a41d-819a036937be",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:16:29.528210"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_7c0533b8-d4ae-457a-a41d-819a036937be"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_7c0533b8-d4ae-457a-a41d-819a036937be"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "safe_rich"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "7c0533b8-d4ae-457a-a41d-819a036937be"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_ef35103a-c228-48a5-9390-4b177ef6110d",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:15:06.606280"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_ef35103a-c228-48a5-9390-4b177ef6110d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_ef35103a-c228-48a5-9390-4b177ef6110d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "exact_embrace"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "ef35103a-c228-48a5-9390-4b177ef6110d"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_be1d1ef5-225f-4795-9842-6792f4ea1e52",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:05:42.754818"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_be1d1ef5-225f-4795-9842-6792f4ea1e52"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_be1d1ef5-225f-4795-9842-6792f4ea1e52"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "immune_machine"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "be1d1ef5-225f-4795-9842-6792f4ea1e52"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "carbon"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_9f231701-1ee0-42e6-8a83-9b968563621d",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:05:10.063416"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_9f231701-1ee0-42e6-8a83-9b968563621d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_9f231701-1ee0-42e6-8a83-9b968563621d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "clever_potato"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "9f231701-1ee0-42e6-8a83-9b968563621d"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_739a60d1-4595-4f63-943f-0d83a572f75c",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessDataSources"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 11:36:18.324344"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_739a60d1-4595-4f63-943f-0d83a572f75c"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_739a60d1-4595-4f63-943f-0d83a572f75c"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "swear_hamster"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "739a60d1-4595-4f63-943f-0d83a572f75c"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_5dee83c2-3b17-4dcf-9bc6-6c6566064d4d",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:24:40.757285"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_5dee83c2-3b17-4dcf-9bc6-6c6566064d4d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_5dee83c2-3b17-4dcf-9bc6-6c6566064d4d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "decorate_region"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "5dee83c2-3b17-4dcf-9bc6-6c6566064d4d"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_fe8ecd33-fec6-4175-a223-28049ce70511",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 11:41:21.352457"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_fe8ecd33-fec6-4175-a223-28049ce70511"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_fe8ecd33-fec6-4175-a223-28049ce70511"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "crack_stadium"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "fe8ecd33-fec6-4175-a223-28049ce70511"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_93901f4b-df6d-44d7-8030-84c3b2377981",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:00:37.779575"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_93901f4b-df6d-44d7-8030-84c3b2377981"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_93901f4b-df6d-44d7-8030-84c3b2377981"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "vicious_usage"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "93901f4b-df6d-44d7-8030-84c3b2377981"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_fc49c7af-1999-4aa2-89a2-3701ee2c572b",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:15:00.836843"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_fc49c7af-1999-4aa2-89a2-3701ee2c572b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_fc49c7af-1999-4aa2-89a2-3701ee2c572b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "riot_universe"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "fc49c7af-1999-4aa2-89a2-3701ee2c572b"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_3cbe2e33-2150-4950-ac7c-1c069a9378c3",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:14:52.938511"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_3cbe2e33-2150-4950-ac7c-1c069a9378c3"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_3cbe2e33-2150-4950-ac7c-1c069a9378c3"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "salon_empty"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "3cbe2e33-2150-4950-ac7c-1c069a9378c3"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_8b5ed944-6526-4819-97ff-3f6070c9e002",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:16:40.314208"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_8b5ed944-6526-4819-97ff-3f6070c9e002"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_8b5ed944-6526-4819-97ff-3f6070c9e002"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "remove_girl"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "8b5ed944-6526-4819-97ff-3f6070c9e002"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "carbon, zinc"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_f22e4f2e-26b8-424e-a969-f0e5a9d0ec6b",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 11:20:10.163539"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_f22e4f2e-26b8-424e-a969-f0e5a9d0ec6b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_f22e4f2e-26b8-424e-a969-f0e5a9d0ec6b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "leopard_dial"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "f22e4f2e-26b8-424e-a969-f0e5a9d0ec6b"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_0b746adc-8e9a-45aa-bd77-bf1dfc086ec2",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:05:46.017071"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_0b746adc-8e9a-45aa-bd77-bf1dfc086ec2"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_0b746adc-8e9a-45aa-bd77-bf1dfc086ec2"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "canoe_drop"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "0b746adc-8e9a-45aa-bd77-bf1dfc086ec2"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "carbon"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_0017653d-40f6-49c9-959c-de6d2f54c15b",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:05:15.597042"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_0017653d-40f6-49c9-959c-de6d2f54c15b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_0017653d-40f6-49c9-959c-de6d2f54c15b"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "report_tumble"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "0017653d-40f6-49c9-959c-de6d2f54c15b"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_03c321d7-ffa8-4fd5-9d05-d8d0401045b2",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:05:50.881096"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_03c321d7-ffa8-4fd5-9d05-d8d0401045b2"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_03c321d7-ffa8-4fd5-9d05-d8d0401045b2"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "reveal_yellow"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "03c321d7-ffa8-4fd5-9d05-d8d0401045b2"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "None"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_265cbf24-14eb-4754-a1ee-eec69d238768",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessTools"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:24:17.673432"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_265cbf24-14eb-4754-a1ee-eec69d238768"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_265cbf24-14eb-4754-a1ee-eec69d238768"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "donor_reward"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "265cbf24-14eb-4754-a1ee-eec69d238768"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_7365b4b6-18ed-402e-baff-663f911f3e25",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:42:43.735227"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_7365b4b6-18ed-402e-baff-663f911f3e25"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_7365b4b6-18ed-402e-baff-663f911f3e25"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "damage_amateur"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "7365b4b6-18ed-402e-baff-663f911f3e25"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_c252ad3e-9858-45e7-a076-2ac0d5bad91d",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:10:11.944935"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_c252ad3e-9858-45e7-a076-2ac0d5bad91d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_c252ad3e-9858-45e7-a076-2ac0d5bad91d"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "inflict_taste"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "c252ad3e-9858-45e7-a076-2ac0d5bad91d"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_cea3b81f-ddab-4feb-9dd1-bb9be122a5ba",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 11:50:44.166741"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_cea3b81f-ddab-4feb-9dd1-bb9be122a5ba"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_cea3b81f-ddab-4feb-9dd1-bb9be122a5ba"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "rabbit_maid"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "cea3b81f-ddab-4feb-9dd1-bb9be122a5ba"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_8b51bc9e-8b39-4f1a-83ff-98425d70075c",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:17:43.284143"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_8b51bc9e-8b39-4f1a-83ff-98425d70075c"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_8b51bc9e-8b39-4f1a-83ff-98425d70075c"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "maximum_hammer"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "8b51bc9e-8b39-4f1a-83ff-98425d70075c"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_8503f5ec-e226-4aef-bbb6-d252dfd65068",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-04 12:04:21.816293"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_8503f5ec-e226-4aef-bbb6-d252dfd65068"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_8503f5ec-e226-4aef-bbb6-d252dfd65068"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "scrub_empty"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "8503f5ec-e226-4aef-bbb6-d252dfd65068"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_a2026eed-e279-4d18-bece-acea68c52956",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#AccessOntology"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 00:15:49.456151"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_a2026eed-e279-4d18-bece-acea68c52956"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_a2026eed-e279-4d18-bece-acea68c52956"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "runway_inform"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "a2026eed-e279-4d18-bece-acea68c52956"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        },
        {
            "@id": "https://www.ddmd.io/mio#cuds_iri_0c911afb-3827-4da3-ac69-8db30713adeb",
            "@type": [
                "http://www.ddmd.io/mio/cuds#Cuds",
                "http://dome40.eu/semantics/pc#SearchActivity"
            ],
            "http://www.ddmd.io/mio/cuds#CreationTime": [
                {
                    "@value": "2024-12-03 10:24:13.933114"
                }
            ],
            "http://www.ddmd.io/mio/cuds#PID": [
                {
                    "@id": "http://www.ddmd.io/mio#cuds_pid_0c911afb-3827-4da3-ac69-8db30713adeb"
                }
            ],
            "http://www.ddmd.io/mio/cuds#description": [
                {
                    "@value": "None"
                }
            ],
            "http://www.ddmd.io/mio/cuds#iri": [
                {
                    "@id": "https://www.ddmd.io/mio#cuds_iri_0c911afb-3827-4da3-ac69-8db30713adeb"
                }
            ],
            "http://www.ddmd.io/mio/cuds#label": [
                {
                    "@value": "logic_obvious"
                }
            ],
            "http://www.ddmd.io/mio/cuds#uuid": [
                {
                    "@value": "0c911afb-3827-4da3-ac69-8db30713adeb"
                }
            ],
            "http://www.w3.org/ns/prov#used": [
                {
                    "@value": "None"
                }
            ],
            "http://www.w3.org/ns/prov#wasAssociatedWith": [
                {
                    "@id": "http://dome40.eu/semantics/pc#User_e5c615e4-35ff-43f0-acc5-35c39ff27c3c"
                }
            ]
        }
    ]
}

```