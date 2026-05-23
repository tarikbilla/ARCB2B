# Product Requirements Document (PRD)
# ArcB2B - B2B E-Commerce Platform for Bangladesh

**Project Name:** ArcB2B  
**Target Market:** Bangladesh B2B Commerce  
**Business Model:** B2B Marketplace (Similar to 1688.com)  
**Document Version:** 1.0  
**Date:** May 23, 2026  
**Development Timeline:** 4 Months  
**Development Budget:** $3,200 USD

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Project Overview](#project-overview)
3. [Core Features](#core-features)
4. [Technical Architecture](#technical-architecture)
5. [Development Timeline](#development-timeline)
6. [Cost Estimation](#cost-estimation)
7. [Database Schema](#database-schema)
8. [API Specifications](#api-specifications)
9. [Security & Compliance](#security-compliance)
10. [Deployment Architecture](#deployment-architecture)

---

## Executive Summary

ArcB2B is a comprehensive B2B e-commerce platform designed for the Bangladesh market, inspired by the successful 1688.com model. The platform connects manufacturers, wholesalers, and retailers, enabling seamless bulk transactions and streamlining the B2B supply chain ecosystem.

**Key Objectives:**
- Connect Bangladeshi manufacturers, wholesalers, and retailers
- Facilitate bulk transactions with transparent pricing
- Provide secure local payment options (bKash, Nagad, Rocket)
- Enable direct supplier-buyer communication
- Streamline logistics with local courier integration

**Project Deliverables:**
- Responsive web application (Next.js)
- Native mobile applications (Android & iOS)
- RESTful API backend (Express.js)
- Admin management panel
- Real-time chat system
- Payment gateway integration
- Logistics API integration

**Total Investment:** $3,351 USD
- Development: $3,200 USD
- Infrastructure (4 months): $151 USD

---

## Project Overview

### Target Audience

**Primary Users:**
- Small to medium-sized retailers and resellers
- Businesses sourcing products in bulk
- Wholesalers and distributors

**Secondary Users:**
- Manufacturers looking to reach wider markets
- Import/export businesses
- International buyers interested in Bangladeshi products

### Value Proposition

**For Buyers:**
- Access to verified local suppliers
- Competitive bulk pricing with tier discounts
- Secure payment options (bKash, Nagad, Rocket)
- Direct communication with suppliers
- RFQ system for custom requirements
- Trade assurance and buyer protection

**For Suppliers:**
- Larger market reach across Bangladesh
- Professional storefront with analytics
- Order management system
- Marketing and promotion tools
- Multiple payment collection options
- Integrated logistics solutions

### Market Opportunity

**Bangladesh E-Commerce Market:**
- Annual growth rate: 30%+
- Internet users: 100+ million
- Mobile wallet users: 80+ million
- SME businesses: 7.8 million
- Major sectors: Garments, Electronics, Food & Beverage, Construction

---

## Core Features

### 1. User Management System

**Buyer Features:**
- Individual and business account registration
- Email and phone verification (OTP)
- Company profile management
- Business license upload
- Multiple shipping addresses
- Purchase history and analytics
- Wishlist and favorites
- Two-factor authentication (2FA)

**Supplier Features:**
- Supplier registration with verification
- Business license verification
- Factory certification upload
- Customizable storefront
- Company profile page (public)
- Store analytics dashboard
- Supplier tier system (Basic, Gold, Premium)
- Follower/subscriber management

### 2. Product Management

**Product Catalog:**
- 20+ main product categories
- Unlimited sub-categories
- Multiple product variants (size, color, material)
- Rich product descriptions (WYSIWYG editor)
- Multiple image upload (up to 20 images per product)
- Product video upload support
- Technical specifications with custom fields
- Product documentation upload (PDF, DOC)
- Certification display (ISO, CE, etc.)

**Inventory Management:**
- Real-time stock tracking
- Multi-warehouse support
- Bulk product upload (CSV/Excel)
- Low stock alerts
- Automatic stock updates on orders

**Pricing Structure:**
- MOQ (Minimum Order Quantity) settings
- Tiered pricing based on quantity
- Bulk discount configuration
- Sample product pricing
- Negotiable pricing options
- Dynamic pricing support

### 3. Search & Discovery

**Search Features:**
- Advanced product search with filters
- Category-based browsing
- Supplier search and filtering
- Price range filters
- MOQ filters
- Location-based search
- Search suggestions and autocomplete
- Recently viewed products
- Product comparison tool

**AI-Powered Features:**
- Image-based product search
- Smart product recommendations
- Personalized search results
- Similar product suggestions

### 4. Order Management System

**Shopping & Ordering:**
- Shopping cart with multiple suppliers
- Draft orders and saved carts
- Order templates for repeat purchases
- Bulk order processing
- Quick order forms

**RFQ (Request for Quotation):**
- Create detailed RFQ requests
- Attach specifications and documents
- Target specific suppliers
- Receive multiple quotations
- Compare quotes side-by-side
- Quote validity period
- Counter-offer negotiation

**Quotation System:**
- Automated quote generation
- Quote-to-order conversion
- Negotiation history tracking
- Accept/reject quotations
- Terms and conditions negotiation

**Order Processing:**
- Order confirmation workflow
- Order status tracking (7 states: Pending, Confirmed, Processing, Shipped, Delivered, Cancelled, Disputed)
- Production progress tracking
- Split shipment management
- Order modification requests
- Order cancellation with rules

**Invoicing:**
- Automated invoice generation (PDF)
- Tax invoice support
- Packing list generation
- Digital invoice archive

### 5. Payment System

**Payment Gateways:**
- bKash merchant integration
- Nagad merchant integration
- Rocket merchant integration
- Bank transfer option
- Payment gateway sandbox testing

**Payment Features:**
- Payment escrow service
- Installment payment options
- Multiple payment methods per order
- Payment reminders (automated)
- Transaction history
- Payment status tracking
- Refund processing

### 6. Communication System

**Real-time Chat:**
- WebSocket-based chat (Socket.io)
- One-on-one buyer-supplier messaging
- File sharing (images, documents up to 10MB)
- Message templates for common queries
- Unread message notifications
- Chat history archive
- Online/offline status indicators

**Inquiry System:**
- Product inquiry forms
- Bulk inquiry submissions
- Automated inquiry routing to suppliers
- Inquiry tracking dashboard
- Response time tracking

**Translation:**
- Auto-translation (Bangla/English)
- Support for product descriptions
- Chat message translation

### 7. Logistics & Shipping

**Courier Integration:**
- Pathao API integration
- Steadfast API integration
- RedX API integration
- eCourier API integration

**Shipping Features:**
- Shipping cost calculator
- Delivery time estimation
- Real-time tracking integration
- Tracking number management
- Proof of Delivery (POD) upload
- Multiple shipping addresses
- Warehouse-to-warehouse shipping
- International shipping options

### 8. Review & Rating System

**Product Reviews:**
- Star ratings (1-5 scale)
- Written reviews with images
- Verified purchase badges
- Review helpful voting
- Review moderation system

**Supplier Ratings:**
- Overall supplier score
- Multi-criteria ratings:
  - Product quality
  - Communication
  - Delivery speed
  - Service quality
- Response rate metrics
- On-time delivery rate

### 9. Analytics & Reporting

**Buyer Analytics:**
- Purchase history analysis
- Spending trends dashboard
- Supplier performance comparison
- Price tracking over time
- Order frequency analysis

**Supplier Analytics:**
- Sales dashboard with charts
- Product performance metrics
- Visitor analytics (page views, unique visitors)
- Conversion rate tracking
- Revenue reports (daily, weekly, monthly, yearly)
- Inventory turnover reports
- Customer demographics
- Top-selling products
- Traffic sources analysis

### 10. Marketing & Promotion Tools

**For Suppliers:**
- Featured product listings
- Banner advertising slots
- Promotional campaigns
- Flash sales creation
- Coupon code generation
- Discount management
- Email campaign tools
- Daily deals participation

**Platform Features:**
- Homepage featured sections
- New arrivals showcase
- Best sellers display
- Category promotions
- Email marketing campaigns
- Push notifications (mobile app)
- Referral program
- Affiliate marketing system

### 11. Mobile Application

**Native Mobile Apps (Android & iOS):**
- All web features optimized for mobile
- Native UI/UX design
- Barcode/QR code scanner
- Mobile-optimized checkout flow
- Push notifications
- Offline mode (cached product viewing)
- Mobile payment integration
- Camera integration for product search
- Biometric authentication
- Deep linking support

### 12. Admin Panel

**Platform Management:**
- User management dashboard
- Supplier verification workflow
- Product approval system
- Order monitoring dashboard
- Content management system (CMS)
- Category management
- Dispute resolution center
- Review moderation
- System settings configuration

**Financial Management:**
- Transaction monitoring
- Commission settings
- Payment reconciliation
- Payout management to suppliers
- Financial reporting
- Revenue analytics

**Analytics Dashboard:**
- Platform-wide statistics
- User growth metrics
- Transaction volume
- Revenue tracking
- Popular categories
- Geographic analytics
- Real-time monitoring

### 13. Security & Trust Features

- SSL/TLS encryption
- Secure payment processing
- Fraud detection system
- Buyer protection policy
- Trade assurance program
- Dispute resolution center
- Data backup and recovery
- GDPR-inspired privacy controls
- Supplier verification badges
- Secure file uploads
- Rate limiting and DDoS protection

### 14. Additional Features

**Customization Services:**
- OEM/ODM service listings
- Custom manufacturing request forms
- Prototype development requests
- Private labeling options

**Documentation:**
- Digital invoice generation
- Packing list templates
- Shipping document management
- Tax invoice support
- Export documentation support

**Multi-language Support:**
- Bangla (primary interface)
- English (secondary)
- Language switcher
- Translatable product content

**SEO & Marketing:**
- SEO-optimized product pages
- Meta tags management
- Sitemap generation
- Social media integration (Open Graph)
- Google Analytics integration
- Facebook Pixel support
- Schema markup for products

---

## Technical Architecture

### Technology Stack

**Frontend (Web Application):**
- Framework: Next.js 14+ (React 18+)
- Language: TypeScript
- Styling: Tailwind CSS
- UI Components: Shadcn/ui
- State Management: Zustand
- Data Fetching: React Query (TanStack Query)
- Forms: React Hook Form
- Validation: Zod
- Animation: Framer Motion
- Icons: Lucide React

**Backend (API Server):**
- Runtime: Node.js 20 LTS
- Framework: Express.js
- Language: JavaScript/TypeScript
- Authentication: JWT (jsonwebtoken)
- Password Hashing: bcrypt
- Real-time: Socket.io
- File Upload: Multer
- Image Processing: Sharp
- Validation: Express Validator
- Security: Helmet.js, CORS
- Rate Limiting: Express Rate Limit

**Database:**
- Primary Database: MongoDB
- ODM: Mongoose
- Caching: Redis
- Session Store: Redis

**Mobile Application:**
- Framework: React Native
- Development Tool: Expo
- State Management: Zustand
- Navigation: React Navigation
- Push Notifications: Expo Notifications

**Infrastructure:**
- Web Server: Nginx (reverse proxy, SSL termination)
- Process Manager: PM2
- SSL Certificate: Let's Encrypt (free)
- CDN: Cloudflare (free tier)

### System Architecture Diagram

```
Client Layer
├── Web Application (Next.js)
│   ├── Server-Side Rendering (SSR)
│   ├── Static Site Generation (SSG)
│   └── API Routes
└── Mobile Applications
    ├── Android (React Native)
    └── iOS (React Native)
    
API Gateway Layer
└── Nginx Reverse Proxy
    ├── SSL Termination
    ├── Load Balancing
    ├── Rate Limiting
    └── Static File Serving

Application Layer
└── Express.js Backend
    ├── Authentication Service
    ├── User Service
    ├── Product Service
    ├── Order Service
    ├── Payment Service
    ├── Chat Service (Socket.io)
    └── Notification Service

Data Layer
├── MongoDB (Primary Database)
├── Redis (Caching & Sessions)
└── Cloud Storage (Images & Files)
    └── Cloudinary or AWS S3

External Services
├── Payment Gateways (bKash, Nagad, Rocket)
├── Courier APIs (Pathao, Steadfast, RedX, eCourier)
├── SMS Gateway (OTP & Notifications)
└── Email Service (SendGrid/SMTP)
```

### API Architecture

**RESTful API Design:**
- Base URL: `https://api.arcb2b.com/v1`
- Authentication: Bearer Token (JWT)
- Response Format: JSON
- Error Handling: Standard HTTP status codes
- Pagination: Cursor-based and offset-based
- Rate Limiting: 100 requests per 15 minutes per IP

**WebSocket (Real-time):**
- Endpoint: `wss://api.arcb2b.com/socket.io`
- Protocol: Socket.io
- Use Cases: Chat, notifications, order updates

---

## Development Timeline

### Overview
- Total Duration: 4 Months
- Development Approach: Agile with weekly sprints
- Team: 2-3 full-time developers
- Working Mode: Synchronous web and mobile app development

### Month 1: Foundation & MVP

**Week 1-2: Setup & Core Infrastructure**
- Development environment setup
- Repository initialization (Git)
- CI/CD pipeline configuration (GitHub Actions)
- Database schema design
- Authentication system (JWT)
- User registration and login (web & mobile)
- Email/SMS OTP verification
- Basic user profile management

**Week 3-4: Product Catalog & Search**
- Product model and CRUD operations
- Category management
- Product listing page (web & mobile)
- Product detail page (web & mobile)
- Image upload and processing
- Basic search functionality
- Product filtering
- Admin panel: User management basics

**Deliverables:**
- Working authentication system
- Basic product catalog
- Simple search functionality
- Admin panel foundation
- Responsive web app
- Mobile app (basic screens)

### Month 2: Core Commerce Features

**Week 1-2: Payment & Order System**
- Shopping cart implementation (web & mobile)
- Order placement workflow
- Payment gateway integration:
  - bKash merchant API
  - Nagad merchant API
  - Rocket merchant API
- Order management system
- Invoice generation
- Email notifications

**Week 3-4: RFQ & Quotation System**
- RFQ creation form (web & mobile)
- Quotation submission system
- Quote comparison interface
- Negotiation workflow
- Accept/reject quotations
- Quote-to-order conversion
- Advanced search with filters
- Supplier verification system

**Deliverables:**
- Complete payment integration
- Order processing system
- RFQ and quotation features
- Enhanced search capabilities
- Supplier verification workflow

### Month 3: Advanced Features & Integration

**Week 1-2: Communication & Logistics**
- Real-time chat implementation (Socket.io)
- File sharing in chat
- Message notifications
- Courier API integration:
  - Pathao API
  - Steadfast API
  - RedX API
  - eCourier API
- Shipping cost calculator
- Tracking number integration
- Review and rating system

**Week 3-4: Mobile App Completion & Analytics**
- Mobile app feature parity with web
- Push notifications setup
- Mobile payment flows
- Barcode scanner
- Analytics dashboard (supplier)
- Sales reports
- Product performance metrics
- Marketing tools (coupons, promotions)
- Tiered pricing implementation

**Deliverables:**
- Real-time chat system
- Logistics integration
- Review system
- Full-featured mobile apps
- Analytics dashboards
- Marketing tools

### Month 4: Optimization & Launch Preparation

**Week 1-2: AI Features & Optimization**
- AI-powered product recommendations
- Image-based product search (basic)
- Performance optimization:
  - Database query optimization
  - Redis caching implementation
  - Image optimization and CDN
  - Code splitting and lazy loading
- SEO optimization
- Multi-language support (Bangla/English)

**Week 3: Testing & Bug Fixes**
- Comprehensive testing:
  - Unit tests
  - Integration tests
  - API testing
  - Mobile app testing (iOS & Android)
  - Cross-browser testing
- Security audit
- Performance testing
- Load testing
- Bug fixes and refinements

**Week 4: Deployment & Launch**
- Production server setup
- Database migration
- SSL certificate installation
- Domain configuration
- CDN setup
- Mobile app store submission:
  - Google Play Store
  - Apple App Store
- Documentation:
  - User guides (buyer & supplier)
  - API documentation
  - Admin manual
- Training sessions
- Soft launch with beta users
- Monitoring setup

**Deliverables:**
- AI-powered features
- Performance-optimized platform
- Fully tested application
- Production deployment
- Mobile apps published
- Complete documentation
- Launch-ready platform

---

## Cost Estimation

| Topic | Amount | Total |
|-------|--------|-------|
| **Development Cost** | **$3200 Total (350,000 BDT)**<br>→ $1,000 at the beginning<br>→ $1,000 at 50% completion<br>→ Remaining balance after publication<br>**Includes:**<br>→ Android application development<br>→ iOS application development<br>→ Web admin dashboard development<br>→ Backend API development<br>→ Deployment and publishing support | **3,200 USD**<br>**350,000 BDT**<br>**(One Time)** |
| **Server Cost**<br>**(12 Months)** | **Hostinger VPS KVM4:**<br>$12.99/month × 24 = $311.76 | **382.57 USD**<br>**(12 Months)** |
| **Database Cost** | **MongoDB:**<br>$8/month × 24 = $192 | |
| **Domain + Email** | 14.99 + 20 = $34.99 | |
| **Platform Fees** | Apple App Store: $99/year<br>Google Play Console: $25 (one-time) | **124 USD** |

---

## Database Schema

### Collections Overview

The MongoDB database consists of 12 primary collections:

1. users - User accounts and authentication
2. suppliers - Supplier business information
3. products - Product catalog
4. categories - Product categories hierarchy
5. orders - Order transactions
6. rfqs - Request for quotations
7. quotations - Supplier quotations
8. messages - Chat messages
9. reviews - Product and supplier reviews
10. transactions - Payment transactions
11. notifications - User notifications
12. analytics - Event tracking for analytics

### Detailed Schema Definitions

**1. Users Collection**

```javascript
{
  _id: ObjectId,
  email: String, // unique, indexed
  phone: String, // unique, indexed
  password: String, // bcrypt hashed
  role: String, // 'buyer' | 'supplier' | 'admin'
  profile: {
    firstName: String,
    lastName: String,
    avatar: String, // URL
    language: String // 'bn' | 'en'
  },
  company: {
    name: String,
    type: String, // 'individual' | 'business'
    businessLicense: String, // file URL
    taxId: String,
    address: {
      street: String,
      city: String,
      district: String,
      country: String,
      zipCode: String,
      coordinates: {
        lat: Number,
        lng: Number
      }
    }
  },
  verification: {
    email: Boolean,
    phone: Boolean,
    business: Boolean,
    verifiedAt: Date
  },
  status: String, // 'active' | 'suspended' | 'pending'
  preferences: {
    notifications: {
      email: Boolean,
      sms: Boolean,
      push: Boolean
    },
    currency: String, // 'BDT' | 'USD'
    language: String
  },
  createdAt: Date,
  updatedAt: Date,
  lastLoginAt: Date
}

// Indexes
users.email: unique
users.phone: unique
users.role: 1
users.company.name: text
```

**2. Suppliers Collection**

```javascript
{
  _id: ObjectId,
  userId: ObjectId, // ref: users
  storeName: String,
  storeSlug: String, // unique, indexed
  description: String,
  logo: String, // URL
  banner: String, // URL
  tier: String, // 'basic' | 'gold' | 'premium'
  badges: [String], // ['verified', 'top_rated', 'fast_shipping']
  rating: {
    overall: Number, // 0-5
    productQuality: Number,
    communication: Number,
    deliverySpeed: Number,
    service: Number,
    totalReviews: Number
  },
  stats: {
    totalProducts: Number,
    totalOrders: Number,
    totalRevenue: Number,
    responseRate: Number, // percentage
    responseTime: Number, // hours
    followers: Number
  },
  businessInfo: {
    registrationNumber: String,
    establishedYear: Number,
    employeeCount: String,
    certifications: [{
      name: String,
      issuer: String,
      file: String, // URL
      expiryDate: Date
    }]
  },
  contact: {
    email: String,
    phone: String,
    website: String,
    socialMedia: {
      facebook: String,
      linkedin: String
    }
  },
  warehouses: [{
    name: String,
    address: Object,
    isDefault: Boolean
  }],
  settings: {
    autoApproveOrders: Boolean,
    minOrderValue: Number,
    acceptsCustomization: Boolean,
    offersOEM: Boolean,
    offersSamples: Boolean
  },
  status: String, // 'active' | 'suspended' | 'pending_verification'
  createdAt: Date,
  updatedAt: Date
}

// Indexes
suppliers.userId: 1
suppliers.storeSlug: unique
suppliers.tier: 1
suppliers.rating.overall: -1
suppliers.storeName: text
suppliers.description: text
```

**3. Products Collection**

```javascript
{
  _id: ObjectId,
  supplierId: ObjectId, // ref: suppliers
  title: String, // indexed
  slug: String, // unique
  description: String,
  shortDescription: String,
  category: ObjectId, // ref: categories
  subCategory: ObjectId,
  images: [{
    url: String,
    alt: String,
    order: Number
  }],
  videos: [String],
  specifications: [{
    key: String,
    value: String
  }],
  variants: [{
    name: String, // e.g., "Red - Large"
    sku: String,
    attributes: {
      color: String,
      size: String,
      material: String
    },
    pricing: {
      basePrice: Number,
      tiers: [{
        minQuantity: Number,
        maxQuantity: Number,
        price: Number,
        discount: Number
      }]
    },
    stock: Number,
    images: [String]
  }],
  pricing: {
    currency: String, // 'BDT' | 'USD'
    basePrice: Number,
    moq: Number, // Minimum Order Quantity
    maxOrderQuantity: Number,
    tiers: [{
      minQty: Number,
      price: Number,
      discountPercent: Number
    }],
    samplePrice: Number,
    sampleAvailable: Boolean
  },
  manufacturing: {
    leadTime: Number, // days
    customizable: Boolean,
    oemAvailable: Boolean,
    odmAvailable: Boolean
  },
  shipping: {
    weight: Number, // kg
    dimensions: {
      length: Number,
      width: Number,
      height: Number
    },
    packagingType: String,
    freeShipping: Boolean
  },
  certifications: [{
    name: String,
    file: String // URL
  }],
  tags: [String],
  seo: {
    metaTitle: String,
    metaDescription: String,
    keywords: [String]
  },
  stats: {
    views: Number,
    inquiries: Number,
    orders: Number,
    revenue: Number,
    averageRating: Number,
    totalReviews: Number
  },
  status: String, // 'draft' | 'active' | 'suspended' | 'out_of_stock'
  featured: Boolean,
  createdAt: Date,
  updatedAt: Date,
  publishedAt: Date
}

// Indexes
products.supplierId: 1
products.category: 1
products.slug: unique
products.status: 1
products.featured: 1, products.createdAt: -1
products.pricing.basePrice: 1
products.title: text
products.description: text
products.tags: text
products.stats.averageRating: -1
```

**4. Categories Collection**

```javascript
{
  _id: ObjectId,
  name: String,
  nameEn: String,
  nameBn: String,
  slug: String, // unique
  description: String,
  icon: String, // URL
  image: String, // URL
  parent: ObjectId, // ref: categories, null for top level
  level: Number, // 0 for top level
  order: Number,
  productCount: Number,
  isActive: Boolean,
  seo: {
    metaTitle: String,
    metaDescription: String
  },
  createdAt: Date,
  updatedAt: Date
}

// Indexes
categories.slug: unique
categories.parent: 1
categories.level: 1, categories.order: 1
```

**5. Orders Collection**

```javascript
{
  _id: ObjectId,
  orderNumber: String, // unique, human-readable
  buyerId: ObjectId, // ref: users
  supplierId: ObjectId, // ref: suppliers
  items: [{
    productId: ObjectId,
    variantId: String,
    title: String,
    image: String,
    sku: String,
    quantity: Number,
    unitPrice: Number,
    totalPrice: Number,
    specifications: Object
  }],
  pricing: {
    subtotal: Number,
    discount: Number,
    shippingCost: Number,
    tax: Number,
    total: Number,
    currency: String
  },
  shippingAddress: {
    name: String,
    phone: String,
    email: String,
    street: String,
    city: String,
    district: String,
    zipCode: String,
    country: String,
    coordinates: Object
  },
  status: String, // 'pending' | 'confirmed' | 'processing' | 'shipped' | 'delivered' | 'cancelled' | 'disputed'
  statusHistory: [{
    status: String,
    timestamp: Date,
    note: String,
    updatedBy: ObjectId
  }],
  payment: {
    method: String, // 'bkash' | 'nagad' | 'rocket' | 'bank_transfer'
    status: String, // 'pending' | 'paid' | 'failed' | 'refunded'
    transactionId: String,
    paidAt: Date,
    escrowReleased: Boolean,
    escrowReleasedAt: Date
  },
  shipping: {
    courier: String, // 'pathao' | 'steadfast' | 'redx' | 'ecourier'
    trackingNumber: String,
    shippedAt: Date,
    deliveredAt: Date,
    estimatedDelivery: Date,
    proof: String // POD image URL
  },
  notes: {
    buyer: String,
    supplier: String,
    admin: String
  },
  rfqId: ObjectId, // ref: rfqs, if order from RFQ
  quotationId: ObjectId, // ref: quotations
  invoice: {
    invoiceNumber: String,
    generatedAt: Date,
    url: String
  },
  createdAt: Date,
  updatedAt: Date
}

// Indexes
orders.orderNumber: unique
orders.buyerId: 1, orders.createdAt: -1
orders.supplierId: 1, orders.createdAt: -1
orders.status: 1
orders.payment.status: 1
orders.createdAt: -1
```

**6. RFQs Collection**

```javascript
{
  _id: ObjectId,
  rfqNumber: String, // unique
  buyerId: ObjectId, // ref: users
  productId: ObjectId, // optional, ref: products
  title: String,
  description: String,
  category: ObjectId,
  specifications: [{
    key: String,
    value: String
  }],
  quantity: Number,
  targetPrice: Number,
  budgetRange: {
    min: Number,
    max: Number
  },
  deliveryDeadline: Date,
  shippingAddress: Object,
  attachments: [String], // file URLs
  status: String, // 'open' | 'quoted' | 'closed' | 'expired'
  targetSuppliers: [ObjectId], // specific suppliers
  quotations: [{
    quotationId: ObjectId,
    supplierId: ObjectId,
    receivedAt: Date
  }],
  expiresAt: Date,
  createdAt: Date,
  updatedAt: Date
}

// Indexes
rfqs.rfqNumber: unique
rfqs.buyerId: 1
rfqs.status: 1, rfqs.expiresAt: 1
rfqs.category: 1
```

**7. Quotations Collection**

```javascript
{
  _id: ObjectId,
  quotationNumber: String,
  rfqId: ObjectId, // ref: rfqs
  supplierId: ObjectId, // ref: suppliers
  buyerId: ObjectId, // ref: users
  items: [{
    description: String,
    specifications: Object,
    quantity: Number,
    unitPrice: Number,
    totalPrice: Number,
    leadTime: Number
  }],
  pricing: {
    subtotal: Number,
    shippingCost: Number,
    tax: Number,
    total: Number,
    currency: String,
    validUntil: Date
  },
  terms: {
    paymentTerms: String,
    deliveryTerms: String,
    warranty: String,
    other: String
  },
  attachments: [String],
  status: String, // 'sent' | 'viewed' | 'accepted' | 'rejected' | 'negotiating' | 'expired'
  negotiationHistory: [{
    by: String, // 'buyer' | 'supplier'
    userId: ObjectId,
    message: String,
    counterOffer: {
      price: Number,
      quantity: Number,
      terms: String
    },
    timestamp: Date
  }],
  acceptedAt: Date,
  rejectedAt: Date,
  expiresAt: Date,
  createdAt: Date,
  updatedAt: Date
}

// Indexes
quotations.quotationNumber: unique
quotations.rfqId: 1
quotations.supplierId: 1
quotations.buyerId: 1
quotations.status: 1
```

**8. Messages Collection**

```javascript
{
  _id: ObjectId,
  conversationId: String, // indexed
  senderId: ObjectId, // ref: users
  receiverId: ObjectId, // ref: users
  message: String,
  messageType: String, // 'text' | 'image' | 'file' | 'product' | 'order'
  attachments: [{
    type: String,
    url: String,
    name: String,
    size: Number
  }],
  metadata: {
    productId: ObjectId,
    orderId: ObjectId,
    quotationId: ObjectId
  },
  isRead: Boolean,
  readAt: Date,
  isDeleted: Boolean,
  deletedBy: [ObjectId],
  createdAt: Date,
  updatedAt: Date
}

// Indexes
messages.conversationId: 1, messages.createdAt: -1
messages.senderId: 1, messages.receiverId: 1
messages.isRead: 1
```

**9. Reviews Collection**

```javascript
{
  _id: ObjectId,
  productId: ObjectId, // ref: products
  supplierId: ObjectId, // ref: suppliers
  buyerId: ObjectId, // ref: users
  orderId: ObjectId, // ref: orders
  rating: {
    overall: Number, // 1-5
    productQuality: Number,
    valueForMoney: Number,
    communication: Number,
    shipping: Number
  },
  review: String,
  images: [String],
  pros: [String],
  cons: [String],
  isVerifiedPurchase: Boolean,
  helpful: {
    count: Number,
    users: [ObjectId]
  },
  supplierResponse: {
    message: String,
    respondedAt: Date
  },
  status: String, // 'pending' | 'approved' | 'rejected'
  moderatedBy: ObjectId,
  moderationNote: String,
  createdAt: Date,
  updatedAt: Date
}

// Indexes
reviews.productId: 1, reviews.createdAt: -1
reviews.supplierId: 1
reviews.buyerId: 1
reviews.orderId: 1
reviews.rating.overall: -1
reviews.isVerifiedPurchase: 1
```

**10. Transactions Collection**

```javascript
{
  _id: ObjectId,
  transactionId: String, // unique
  orderId: ObjectId, // ref: orders
  buyerId: ObjectId,
  supplierId: ObjectId,
  amount: Number,
  currency: String,
  type: String, // 'payment' | 'refund' | 'commission' | 'payout'
  method: String, // 'bkash' | 'nagad' | 'rocket' | 'bank'
  gateway: {
    provider: String,
    transactionId: String,
    response: Object
  },
  status: String, // 'pending' | 'completed' | 'failed' | 'refunded'
  escrow: {
    held: Boolean,
    releasedAt: Date
  },
  commission: {
    rate: Number,
    amount: Number
  },
  metadata: Object,
  createdAt: Date,
  updatedAt: Date,
  completedAt: Date
}

// Indexes
transactions.transactionId: unique
transactions.orderId: 1
transactions.buyerId: 1
transactions.supplierId: 1
transactions.status: 1
transactions.createdAt: -1
```

**11. Notifications Collection**

```javascript
{
  _id: ObjectId,
  userId: ObjectId, // ref: users
  type: String, // 'order' | 'payment' | 'message' | 'review' | 'system'
  title: String,
  message: String,
  data: Object, // additional context
  channels: {
    inApp: Boolean,
    email: Boolean,
    sms: Boolean,
    push: Boolean
  },
  status: {
    inApp: String, // 'unread' | 'read' | 'deleted'
    email: String, // 'pending' | 'sent' | 'failed'
    sms: String,
    push: String
  },
  actionUrl: String,
  priority: String, // 'low' | 'medium' | 'high' | 'urgent'
  expiresAt: Date,
  readAt: Date,
  createdAt: Date
}

// Indexes
notifications.userId: 1, notifications.createdAt: -1
notifications.status.inApp: 1
notifications.type: 1
```

**12. Analytics Collection**

```javascript
{
  _id: ObjectId,
  entity: String, // 'product' | 'supplier' | 'order' | 'user'
  entityId: ObjectId,
  eventType: String, // 'view' | 'inquiry' | 'add_to_cart' | 'purchase'
  userId: ObjectId, // optional
  sessionId: String,
  metadata: {
    page: String,
    source: String,
    device: String,
    browser: String,
    location: Object
  },
  value: Number, // monetary value if applicable
  timestamp: Date,
  date: Date, // for date-based aggregation
  hour: Number
}

// Indexes
analytics.entity: 1, analytics.entityId: 1, analytics.timestamp: -1
analytics.eventType: 1, analytics.timestamp: -1
analytics.userId: 1
analytics.date: -1
```

---

## API Specifications

### Authentication Endpoints

```
POST   /api/auth/register
POST   /api/auth/login
POST   /api/auth/logout
POST   /api/auth/refresh
POST   /api/auth/forgot-password
POST   /api/auth/reset-password
POST   /api/auth/verify-email
POST   /api/auth/verify-phone
POST   /api/auth/resend-otp
```

### User Management

```
GET    /api/users/me
PUT    /api/users/me
PUT    /api/users/me/password
GET    /api/users/:id
POST   /api/users/me/avatar
DELETE /api/users/me/avatar
GET    /api/users/me/addresses
POST   /api/users/me/addresses
PUT    /api/users/me/addresses/:id
DELETE /api/users/me/addresses/:id
```

### Supplier Management

```
GET    /api/suppliers
GET    /api/suppliers/:id
POST   /api/suppliers (create store)
PUT    /api/suppliers/:id
GET    /api/suppliers/:id/products
GET    /api/suppliers/:id/reviews
POST   /api/suppliers/:id/follow
DELETE /api/suppliers/:id/follow
GET    /api/suppliers/:id/analytics
```

### Product Management

```
GET    /api/products
GET    /api/products/:id
POST   /api/products
PUT    /api/products/:id
DELETE /api/products/:id
POST   /api/products/:id/images
DELETE /api/products/:id/images/:imageId
POST   /api/products/bulk-upload
GET    /api/products/:id/variants
POST   /api/products/:id/variants
PUT    /api/products/:id/variants/:variantId
DELETE /api/products/:id/variants/:variantId
POST   /api/products/:id/inquiry
GET    /api/products/search
GET    /api/products/categories/:categoryId
GET    /api/products/:id/similar
POST   /api/products/:id/track-view
```

### Category Management

```
GET    /api/categories
GET    /api/categories/:id
GET    /api/categories/:id/subcategories
GET    /api/categories/:id/products
```

### Order Management

```
GET    /api/orders
GET    /api/orders/:id
POST   /api/orders
PUT    /api/orders/:id/status
POST   /api/orders/:id/cancel
GET    /api/orders/:id/tracking
GET    /api/orders/:id/invoice
POST   /api/orders/:id/review
```

### Cart Management

```
GET    /api/cart
POST   /api/cart/items
PUT    /api/cart/items/:itemId
DELETE /api/cart/items/:itemId
DELETE /api/cart
```

### RFQ & Quotations

```
GET    /api/rfqs
GET    /api/rfqs/:id
POST   /api/rfqs
PUT    /api/rfqs/:id
DELETE /api/rfqs/:id
GET    /api/rfqs/:id/quotations
POST   /api/quotations
GET    /api/quotations/:id
PUT    /api/quotations/:id
POST   /api/quotations/:id/accept
POST   /api/quotations/:id/reject
POST   /api/quotations/:id/negotiate
```

### Messaging

```
GET    /api/messages/conversations
GET    /api/messages/conversations/:conversationId
POST   /api/messages
PUT    /api/messages/:id/read
DELETE /api/messages/:id
POST   /api/messages/upload
GET    /api/messages/unread-count
```

### Reviews

```
GET    /api/reviews
POST   /api/reviews
PUT    /api/reviews/:id
DELETE /api/reviews/:id
POST   /api/reviews/:id/helpful
POST   /api/reviews/:id/response (supplier)
GET    /api/reviews/product/:productId
GET    /api/reviews/supplier/:supplierId
```

### Payment

```
POST   /api/payments/initiate
POST   /api/payments/callback/bkash
POST   /api/payments/callback/nagad
POST   /api/payments/callback/rocket
GET    /api/payments/:transactionId
POST   /api/payments/:orderId/refund
GET    /api/payments/methods
```

### Shipping

```
GET    /api/shipping/couriers
POST   /api/shipping/calculate
POST   /api/shipping/book
GET    /api/shipping/track/:trackingNumber
```

### Analytics

```
GET    /api/analytics/dashboard
GET    /api/analytics/sales
GET    /api/analytics/products
GET    /api/analytics/customers
GET    /api/analytics/revenue
GET    /api/analytics/traffic
```

### Notifications

```
GET    /api/notifications
PUT    /api/notifications/:id/read
PUT    /api/notifications/read-all
DELETE /api/notifications/:id
GET    /api/notifications/unread-count
PUT    /api/notifications/settings
```

### Admin Endpoints

```
GET    /api/admin/users
PUT    /api/admin/users/:id/status
GET    /api/admin/suppliers/pending
PUT    /api/admin/suppliers/:id/verify
GET    /api/admin/products/pending
PUT    /api/admin/products/:id/approve
GET    /api/admin/orders
PUT    /api/admin/orders/:id
GET    /api/admin/reviews/pending
PUT    /api/admin/reviews/:id/moderate
GET    /api/admin/analytics
PUT    /api/admin/settings
GET    /api/admin/transactions
```

### WebSocket Events (Socket.io)

**Client to Server:**
```
authenticate
join_conversation
leave_conversation
send_message
typing_start
typing_stop
mark_read
```

**Server to Client:**
```
message_received
message_sent
typing
read_receipt
new_notification
order_update
connection_status
```

---

## Security & Compliance

### Authentication & Authorization

**JWT Token Implementation:**
- Access Token: 15 minutes expiry
- Refresh Token: 7 days expiry
- Token stored in httpOnly cookies (web)
- Secure token storage (mobile keychain/keystore)
- Role-based access control (RBAC)
- Permission-based authorization

**Password Security:**
- bcrypt hashing (cost factor: 10)
- Minimum password length: 8 characters
- Password complexity requirements
- Password reset with time-limited tokens
- Account lockout after 5 failed attempts

### Data Security

**Encryption:**
- SSL/TLS for all communications
- Database encryption at rest
- Sensitive data field-level encryption
- Secure file storage with signed URLs

**Input Validation:**
- Express Validator for all inputs
- MongoDB injection prevention
- XSS protection (sanitization)
- CSRF token protection
- File upload validation (type, size)

**API Security:**
- Rate limiting (100 requests/15 min per IP)
- API key authentication for webhooks
- Request size limits
- CORS configuration
- Security headers (Helmet.js)

### Privacy & Compliance

**Data Privacy:**
- GDPR-inspired data handling
- User data export functionality
- Right to be forgotten (data deletion)
- Privacy policy and terms of service
- Cookie consent management
- Data anonymization for analytics

**Payment Security:**
- PCI-DSS compliance via payment gateways
- No storage of sensitive payment data
- Tokenized payment information
- Secure payment callback verification
- Transaction logging and audit trail

### Backup & Recovery

**Database Backup:**
- Automated daily backups
- Point-in-time recovery capability
- 30-day backup retention
- Backup encryption
- Regular backup restoration testing

**Disaster Recovery:**
- Redundant server configuration
- Database replication
- CDN for static assets
- Recovery time objective (RTO): 4 hours
- Recovery point objective (RPO): 24 hours

---

## Deployment Architecture

### Production Environment Setup

**Server Configuration:**
- Operating System: Ubuntu 22.04 LTS
- Web Server: Nginx 1.24+
- Process Manager: PM2
- Node.js Version: 20 LTS
- MongoDB: 7.0+
- Redis: 7.0+

### Nginx Configuration

```nginx
upstream backend {
    server 127.0.0.1:5000;
    keepalive 64;
}

upstream nextjs {
    server 127.0.0.1:3000;
    keepalive 64;
}

server {
    listen 80;
    server_name arcb2b.com www.arcb2b.com;
    return 301 https://$server_name$request_uri;
}

server {
    listen 443 ssl http2;
    server_name arcb2b.com www.arcb2b.com;

    ssl_certificate /etc/letsencrypt/live/arcb2b.com/fullchain.pem;
    ssl_certificate_key /etc/letsencrypt/live/arcb2b.com/privkey.pem;
    ssl_protocols TLSv1.2 TLSv1.3;
    ssl_ciphers HIGH:!aNULL:!MD5;

    # Security headers
    add_header X-Frame-Options "SAMEORIGIN" always;
    add_header X-Content-Type-Options "nosniff" always;
    add_header X-XSS-Protection "1; mode=block" always;
    add_header Strict-Transport-Security "max-age=31536000" always;

    # API Routes
    location /api {
        proxy_pass http://backend;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header X-Forwarded-Proto $scheme;
    }

    # WebSocket (Socket.io)
    location /socket.io {
        proxy_pass http://backend;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection "upgrade";
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }

    # Next.js Frontend
    location / {
        proxy_pass http://nextjs;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }

    # Static files caching
    location ~* \.(jpg|jpeg|png|gif|ico|css|js|svg|woff|woff2|ttf|eot)$ {
        expires 1y;
        add_header Cache-Control "public, immutable";
    }

    client_max_body_size 20M;
}
```

### PM2 Configuration

```javascript
// ecosystem.config.js
module.exports = {
  apps: [
    {
      name: 'arcb2b-backend',
      script: './backend/src/server.js',
      instances: 2,
      exec_mode: 'cluster',
      env: {
        NODE_ENV: 'production',
        PORT: 5000
      },
      max_memory_restart: '500M',
      error_file: './logs/backend-error.log',
      out_file: './logs/backend-out.log',
      log_date_format: 'YYYY-MM-DD HH:mm:ss Z'
    },
    {
      name: 'arcb2b-frontend',
      script: 'npm',
      args: 'start',
      cwd: './frontend',
      instances: 1,
      env: {
        NODE_ENV: 'production',
        PORT: 3000
      },
      max_memory_restart: '500M',
      error_file: './logs/frontend-error.log',
      out_file: './logs/frontend-out.log'
    }
  ]
};
```

### Environment Variables

```bash
# .env.production

# Application
NODE_ENV=production
PORT=5000
FRONTEND_URL=https://arcb2b.com
API_URL=https://api.arcb2b.com

# Database
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/arcb2b?retryWrites=true&w=majority
REDIS_URL=redis://localhost:6379

# JWT
JWT_SECRET=your-super-secret-jwt-key-change-this
JWT_EXPIRES_IN=15m
REFRESH_TOKEN_SECRET=your-refresh-token-secret
REFRESH_TOKEN_EXPIRES_IN=7d

# Payment Gateways
BKASH_APP_KEY=your-bkash-app-key
BKASH_APP_SECRET=your-bkash-secret
BKASH_USERNAME=your-username
BKASH_PASSWORD=your-password
BKASH_BASE_URL=https://checkout.pay.bkash.com

NAGAD_MERCHANT_ID=your-merchant-id
NAGAD_PUBLIC_KEY=your-public-key
NAGAD_PRIVATE_KEY=your-private-key

ROCKET_MERCHANT_ID=your-rocket-merchant-id
ROCKET_API_KEY=your-rocket-api-key

# SMS Gateway
SMS_API_KEY=your-sms-api-key
SMS_SENDER_ID=ArcB2B

# Email
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=noreply@arcb2b.com
SMTP_PASS=your-email-password

# Cloud Storage (Cloudinary)
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret

# Courier APIs
PATHAO_CLIENT_ID=your-pathao-client-id
PATHAO_CLIENT_SECRET=your-pathao-secret
STEADFAST_API_KEY=your-steadfast-key
REDX_API_KEY=your-redx-key
ECOURIER_API_KEY=your-ecourier-key
```

### CI/CD Pipeline

**GitHub Actions Workflow:**

```yaml
name: Deploy to Production

on:
  push:
    branches:
      - main

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: '20'
      - run: npm ci
      - run: npm test

  deploy:
    needs: test
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Deploy to Server
        uses: appleboy/ssh-action@master
        with:
          host: ${{ secrets.HOST }}
          username: ${{ secrets.USERNAME }}
          key: ${{ secrets.SSH_KEY }}
          script: |
            cd /var/www/arcb2b
            git pull origin main
            npm install
            npm run build
            pm2 restart ecosystem.config.js
```

### Monitoring & Logging

**Monitoring Tools:**
- PM2 monitoring dashboard
- MongoDB Atlas monitoring
- Nginx access and error logs
- Application logs (Winston)
- Performance monitoring (New Relic or similar)

**Log Management:**
- Centralized logging
- Log rotation
- Error tracking and alerting
- Performance metrics
- Uptime monitoring

### Mobile App Deployment

**Android (Google Play Store):**
- Build type: Release APK/AAB
- Signing: Keystore file
- Version code increment
- Release track: Production
- Target API level: 33+

**iOS (Apple App Store):**
- Build type: Release IPA
- Signing: Distribution certificate
- Version increment
- TestFlight beta testing
- App Store submission

---

## Appendix

### Technology Dependencies

**Backend Package.json:**

```json
{
  "name": "arcb2b-backend",
  "version": "1.0.0",
  "dependencies": {
    "express": "^4.18.2",
    "mongoose": "^8.0.3",
    "socket.io": "^4.6.1",
    "jsonwebtoken": "^9.0.2",
    "bcryptjs": "^2.4.3",
    "cors": "^2.8.5",
    "helmet": "^7.1.0",
    "express-rate-limit": "^7.1.5",
    "express-validator": "^7.0.1",
    "multer": "^1.4.5-lts.1",
    "sharp": "^0.33.2",
    "nodemailer": "^6.9.8",
    "axios": "^1.6.5",
    "dotenv": "^16.3.1",
    "redis": "^4.6.12",
    "morgan": "^1.10.0",
    "compression": "^1.7.4",
    "express-mongo-sanitize": "^2.2.0",
    "uuid": "^9.0.1"
  }
}
```

**Frontend Package.json:**

```json
{
  "name": "arcb2b-frontend",
  "version": "1.0.0",
  "dependencies": {
    "next": "^14.0.4",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "tailwindcss": "^3.4.1",
    "@tanstack/react-query": "^5.17.9",
    "zustand": "^4.4.7",
    "axios": "^1.6.5",
    "socket.io-client": "^4.6.1",
    "react-hook-form": "^7.49.3",
    "zod": "^3.22.4",
    "@hookform/resolvers": "^3.3.4",
    "framer-motion": "^10.18.0",
    "lucide-react": "^0.303.0",
    "date-fns": "^3.0.6",
    "recharts": "^2.10.4"
  }
}
```

### Glossary

**B2B:** Business-to-Business commerce
**MOQ:** Minimum Order Quantity
**RFQ:** Request for Quotation
**OEM:** Original Equipment Manufacturer
**ODM:** Original Design Manufacturer
**POD:** Proof of Delivery
**SKU:** Stock Keeping Unit
**API:** Application Programming Interface
**JWT:** JSON Web Token
**SSL/TLS:** Secure Sockets Layer / Transport Layer Security
**CDN:** Content Delivery Network
**CORS:** Cross-Origin Resource Sharing
**OTP:** One-Time Password
**RBAC:** Role-Based Access Control
**CRUD:** Create, Read, Update, Delete

### Contact Information

**Project Repository:** https://github.com/tarikbilla/ARCB2B
**Documentation:** docs/PRD.md
**Version:** 1.0
**Last Updated:** May 23, 2026

---

**End of Document**
