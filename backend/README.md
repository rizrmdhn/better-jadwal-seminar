# Jadwal Seminar API

## API Documentation

### Get Seminar

Endpoint: GET `/seminars`

Query Parameters:

- `page` (optional): Page number, default is 1
- `limit` (optional): Number of items per page, default is 10

Response Body:

```
{
  "success": true,
  "meta": {
    "page": 1,
    "limit": 10,
    "pageCount": 1
  },
  "data: {
    lastUpdated: "2025-01-01T00:00:00.000Z",
    seminars: [
      {
        "title": "Pengembangan Sistem Pengenalan Wajah Menggunakan Convolutional Neural Networks (CNN)",
        "seminarType": "Seminar 2",
        "studentName": "David Ng",
        "major": "TI",
        "room": " Ruangan X",
        "datetime": "2025-01-30T02:00:00.000Z",
        "advisors": [
          "Jack Tester MSc CS",
          "John Doe MSc CS"
        ],
        "examiners": [
          "Richard Roe MSc AI"
        ]
      },
      {
        "title": "Optimasi Deteksi Ancaman Siber pada Infrastruktur Cloud Menggunakan Wazuh SIEM",
        "seminarType": "Seminar 1",
        "studentName": "William Smith",
        "major": "TI",
        "room": " Ruangan Y",
        "datetime": "2025-01-30T02:00:00.000Z",
        "advisors": [
          "Eve Everywoman MSc CS",
          "Max Everyman MSc CS"
        ],
        "examiners": [
          "Jill Placeholder MCS"
        ]
      }
    ]
  }
}
```
