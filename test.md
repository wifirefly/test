### Request |                       | ### Handle                         | ### Response
    getRequestedPage                |   validateRequest                  |   showResponsePage
GET         |   HOME                |

GET         |   CONTACT             |
POST        |   CONTACT             |   validate Contact                 |    HOME

GET         |   ARTICLE(logged in)  |
AJAX        |   ARTICLE(logged in)  |

GET         |   ABOUT               |

GET         |   AUTHOR              |

GET         |   REGISTER            |
POST        |   REGISTER            |

GET         |   ARTICLE(logged out) |

GET         |   LOGIN               |
POST        |   LOGIN               |   validate Login                    | Login true
                                                                            Home
                                                                            else
                                                                            

GET         |   SEARCH              |

POST        |   SEARCH RESULTS      |

GET         |   MY ARTICLES         |
POST        |   MY ARTICLES         |
AJAX        |   MY ARTICLES         |

POST        |   ARTICLE EDITOR(edit)|
AJAX        |   ARTICLE EDITOR(edit)|
    
GET         |   ARTICLE EDITOR(new) |
POST        |   ARTICLE EDITOR(new) |
AJAX        |   ARTICLE EDITOR(new) |
