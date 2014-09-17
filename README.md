Taxonomies
==========

Raw taxonomy files for the Chicago School of Data project

.json file, which defines a data ecosystem structure.

Defined as follows, "-->" and "<--" represent beginning and end of comments, respectively. 

{
  "name": "DataEcosystem",  --> IN THE DATA ECOSYSTEM <--
  "children": [
    {
      "name": "Creators", --> THERE ARE CREATORS, WHICH INCLUDE <--
      "children": [
        {
          "name": "Open", --> OPEN DATA CREATORS WHO OFFER DATA <--
          "children": [
            {
              "name": "ToPub" --> TO THE PUBLIC <--
            },
            {
              "name": "ToOrgs" --> AND TO ORGANIZATIONS <--
            },
            {
              "name": "Shrbl" --> IN A DISTRIBUTABLE FORMAT <--
            },
            {
              "name": "Free" --> FOR FREE <--
            }
          ]
        },
        {
          "name": "OpenAtCost", --> AND THERE ARE OPEN DATA CREATORS WHO OFFER DATA <--
          "children": [
            {
              "name": "ToPub" --> TO THE PUBLIC <--
            },
            {
              "name": "ToOrgs" --> AND TO ORGANIZATIONS <--
            },
            {
              "name": "Shrbl" --> IN A DISTRIBUTABLE FORMAT <--
            },
            {
              "name": "ForCost" --> FOR A FEE <--
            }
          ]
        },
        {
          "name": "Closed", --> AND THERE ARE DATA CREATORS WHO CAN'T SHARE THEIR DATA <--
          "children": [
            {
              "name": "TechCap" --> BECAUSE OF LIMITED TECHNICAL CAPACITY <--
            },
            {
              "name": "Cost" --> OR THE PRICE <--
            },
            {
              "name": "Lgl" --> OR LEGAL AGREEMENTS <--
            },
            {
              "name": "PubInt" --> OR THE PUBLIC INTEREST <--
            },
            {
              "name": "Othr" --> OR OTHER REASONS <--
            }
          ]
        }
      ]
    },
    {
      "name": "Consumers",  --> AMONG CONSUMERS OF DATA IN THE ECOSYSTEM <--
      "children": [
        {
          "name": "ForFree", --> THERE ARE ORGANIZATIONS WHO CONSUME FREE DATA <--
          "children": [
            {
              "name": "FrmPub" --> THAT WAS CREATED BY PUBLIC INSTITUTIONS <--
            },
            {
              "name": "FrmNFP" --> OR BY A NON PROFIT <--
            },
            {
              "name": "FrmCmp" --> OR A COMPANY <--
            },
            {
              "name": "Elswhr" --> OR BY SOMEONE ELSE <--
            }
          ]
        },
        {
          "name": "Pays", --> AND THERE ARE ORGANIZATIONS WHO  PAY FOR THEIR DATA <--
          "children": [
            {
              "name": "FrmPub" --> THAT WAS CREATED BY A PUBLIC INSTITUTION <--
            },
            {
              "name": "FrmNFP" --> OR BY A NON PROFIT <--
            },
            {
              "name": "FrmCmp" --> OR A COMPANY <--
            },
            {   
              "name": "Elswhr" --> OR BY SOMEONE ELSE <--
            }
          ]
        },
        {
          "name": "Products", --> THESE ORGANIZATIONS USE DATA TO <--
          "children": [
            {
              "name": "IntEval" --> EVALUATE THEIR OWN OPERATIONS <--
            },
            {
              "name": "ExtEval" --> EVALUATE OTHER ORGANIZATIONS' OPERATIONS <--
            },
            {
              "name": "DigMda" --> AND TURNED THE DATA INTO DIGITAL MEDIA <--
            },
            {
              "name": "PrntMda" --> AND TURNED THE DATA INTO PRINT MEDIA <--
            }
          ]
        }
      ]
    },
      "name": "Enablers",  -->THE DATA ECOSYSTEM HAS ENABLERS, SUCH AS<--
      "children": [
        {
          "name": "Volunteer", --> VOLUNTEERS WHO <--
          "children": [
            {
              "name": "Srvcs"  --> PROVIDE SERVICES TO THE ECOSYSTEM<--
            },
            {
              "children": [
                {
                  "name": "Train" --> THROUGH TRAINING <--
                },
                {
                  "name": "Anlys" --> OR ANALYSIS <--
                },
                {
                  "name": "Othr" --> OR IN ANOTHER WAY <--
                }
              ]
            },
            {
              "children": [
                {
                  "name": "Goods" --> OR THEY PROVIDE GOODS TO THE DATA ECOSYSTEM <--
                },
                {
                  "children": [
                    {
                      "name": "Hrdwr" --> LIKE HARDWARE <--
                    },
                    {
                      "name": "Need" --> OR BASIC MATERIAL NEEDS <--
                    },
                    {
                      "name": "Othr" --> OR OTHER GOODS <--
                    }
                  ]
                }
              ]
            }
          ]
        },
        {
          "name": "Funded", --> AND THERE ARE FUNDED ORGANIZATIONS <--
          "children": [
            {
              "name": "Srvcs" -->THAT  PROVIDE SERVICES TO THE ECOSYSTEM<--
            },
            {
              "children": [
                {
                  "name": "Train" --> THROUGH TRAINING <--
                },
                {
                  "name": "Anlys" --> OR ANALYSIS <--
                },
                {
                  "name": "Othr" --> OR IN ANOTHER WAY <--
                }
              ]
            },
            {
              "children": [
                {
                  "name": "Goods" --> OR THEY PROVIDE GOODS TO THE ECOSYSTEM<--
                },
                {
                  "children": [
                    {
                      "name": "Hrdwr" --> LIKE HARDWARE <--
                    },
                    {
                      "name": "Need" --> OR BASIC MATERIAL NEEDS <--
                    },
                    {
                      "name": "Othr" --> OR OTHER GOODS <--
                    }
                  ]
                }
              ]
            }
          ]
        },
        {
          "name": "Paid", --> AND THEN THERE ARE PAID ORGANIZATIONS <--
          "children": [
            {
              "name": "Srvcs" --> WHO PROVIDE SERVICES TO THE ECOSYSTEM<--
            },
            {
              "children": [
                {
                  "name": "Train" --> THROUGH TRAINING <--
                },
                {
                  "name": "Anlys" --> OR ANALYSIS <--
                },
                {
                  "name": "Othr" --> OR IN ANOTHER WAY <--
                }
              ]
            }
          ]
        },
        {
          "children": [
            {
              "name": "Goods" --> OR THEY PROVIDE GOODS TO THE ECOSYSTEM<--
            },
            {
              "children": [
                {
                  "name": "Hrdwr" --> LIKE HARDWARE <--
                },
                {
                  "name": "Need" --> OR BASIC MATERIAL NEEDS <--
                },
                {
                  "name": "Othr" --> OR OTHER GOODS <--
                }
              ]
            }
          ]
        }
      ]
    }
  ]
}
