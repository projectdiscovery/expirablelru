# expirablelru

expirablelru implements a TTL expiring LRU cache based on the one at https://github.com/hashicorp/golang-lru/pull/68 which in turn is based on https://github.com/hashicorp/golang-lru. All thanks go to @paskal and the hashicorp team.

Only difference is the addition of the AddWithTTL method which allows
users to set a TTL per-item.

