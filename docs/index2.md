
### Read Config




| Method | URL |
|--------|-----|
| GET | /api/config |

#### Parameters
| Name | In | Description | Required |
|------|----|-------------|----------|

##### Response (200)
| Field | Type | Description |
|-------|------|-------------|

---

### Error




| Method | URL |
|--------|-----|
| POST | /api/error |

#### Parameters
| Name | In | Description | Required |
|------|----|-------------|----------|

##### Response (200)
| Field | Type | Description |
|-------|------|-------------|

---

### Disconnet




| Method | URL |
|--------|-----|
| POST | /api/disconnet |

#### Parameters
| Name | In | Description | Required |
|------|----|-------------|----------|

##### Response (200)
| Field | Type | Description |
|-------|------|-------------|

---

### Cancel Order




| Method | URL |
|--------|-----|
| POST | /api/cancelorder |

#### Parameters
| Name | In | Description | Required |
|------|----|-------------|----------|
| a | query |  | Required |
| b | query |  | Required |

##### Response (200)
| Field | Type | Description |
|-------|------|-------------|

##### Response (422)
| Field | Type | Description |
|-------|------|-------------|
| detail | array |  |

---

### Cancel Trade




| Method | URL |
|--------|-----|
| POST | /api/canceltrade |

#### Parameters
| Name | In | Description | Required |
|------|----|-------------|----------|

##### Response (200)
| Field | Type | Description |
|-------|------|-------------|

---
