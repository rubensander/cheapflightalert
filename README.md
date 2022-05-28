# cheapflightalert
Use Ryanair and Eurowings API to find cheap connections on selected routes to find the cheapest flights.



Eurowings uses POST requests to
https://www.eurowings.com/en/booking/flights/flight-search/book-flights/select.booking.json?action=QUERY_FLIGHT_DATA
using a payload as in the example file eurowings-request.json


Ryanair uses GET requests like
https://www.ryanair.com/api/farfnd/3/roundTripFares/FCO/CGN/cheapestPerDay?outboundDateFrom=2022-05-27&outboundDateTo=2022-08-20&inboundDateFrom=2022-05-30&inboundDateTo=2022-08-20