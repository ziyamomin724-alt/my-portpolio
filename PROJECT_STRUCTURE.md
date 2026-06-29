# Hidden Bean Café - Project Structure

This document describes the complete production-ready folder structure for the Hidden Bean Café full stack application.

## Root Structure

HiddenBeanCafe/
  ├── client/
  │   ├── assets/
  │   │   ├── css/
  │   │   │   ├── bootstrap.min.css
  │   │   │   ├── style.css
  │   │   ├── js/
  │   │   │   ├── app.js
  │   │   │   ├── auth.js
  │   │   │   ├── cart.js
  │   │   │   ├── swiper-bundle.min.js
  │   │   ├── images/
  │   │   │   ├── hero.jpg
  │   │   │   ├── gallery/
  │   │   │   ├── menu/
  │   │   │   ├── products/
  │   │   │   ├── team/
  │   │   │   ├── testimonials/
  │   │   ├── fonts/
  │   │   ├── vendors/
  │   ├── components/
  │   │   ├── header.html
  │   │   ├── footer.html
  │   │   ├── navbar.html
  │   │   ├── hero.html
  │   │   ├── testimonials.html
  │   ├── pages/
  │   │   ├── about.html
  │   │   ├── cart.html
  │   │   ├── checkout.html
  │   │   ├── contact.html
  │   │   ├── gallery.html
  │   │   ├── index.html
  │   │   ├── login.html
  │   │   ├── menu.html
  │   │   ├── order-history.html
  │   │   ├── payment-failed.html
  │   │   ├── payment-success.html
  │   │   ├── profile.html
  │   │   ├── reset-password.html
  │   │   ├── signup.html
  │   │   ├── track-order.html
  │   │   ├── wishlist.html
  │   │   ├── book-table.html
  │   │   ├── feedback.html
  │   │   ├── admin/
  │   │   │   ├── dashboard.html
  │   │   │   ├── orders.html
  │   │   │   ├── products.html
  │   │   │   ├── bookings.html
  │   │   │   ├── users.html
  │   │   │   ├── reports.html
  │   │   │   ├── settings.html
  │   └── index.html
  ├── server/
  │   ├── config/
  │   │   ├── db.js
  │   │   ├── mailer.js
  │   │   ├── passport.js
  │   │   ├── roles.js
  │   ├── controllers/
  │   │   ├── adminController.js
  │   │   ├── authController.js
  │   │   ├── bookingController.js
  │   │   ├── orderController.js
  │   │   ├── paymentController.js
  │   │   ├── productController.js
  │   │   ├── reviewController.js
  │   │   ├── userController.js
  │   │   ├── wishlistController.js
  │   ├── middleware/
  │   │   ├── authMiddleware.js
  │   │   ├── csrfMiddleware.js
  │   │   ├── errorHandler.js
  │   │   ├── rateLimiter.js
  │   │   ├── validationMiddleware.js
  │   ├── models/
  │   │   ├── Admin.js
  │   │   ├── Booking.js
  │   │   ├── Category.js
  │   │   ├── Coupon.js
  │   │   ├── Notification.js
  │   │   ├── Order.js
  │   │   ├── Product.js
  │   │   ├── Review.js
  │   │   ├── User.js
  │   │   ├── Wishlist.js
  │   ├── routes/
  │   │   ├── adminRoutes.js
  │   │   ├── authRoutes.js
  │   │   ├── bookingRoutes.js
  │   │   ├── orderRoutes.js
  │   │   ├── paymentRoutes.js
  │   │   ├── productRoutes.js
  │   │   ├── reviewRoutes.js
  │   │   ├── userRoutes.js
  │   │   ├── wishlistRoutes.js
  │   ├── services/
  │   │   ├── authService.js
  │   │   ├── orderService.js
  │   │   ├── paymentService.js
  │   │   ├── productService.js
  │   │   ├── userService.js
  │   ├── utils/
  │   │   ├── apiResponse.js
  │   │   ├── errorResponse.js
  │   │   ├── generateToken.js
  │   │   ├── pagination.js
  │   ├── uploads/
  │   │   ├── products/
  │   │   ├── profiles/
  │   │   ├── banners/
  │   ├── views/
  │   │   ├── emails/
  │   │   │   ├── resetPassword.html
  │   │   │   ├── orderConfirmation.html
  │   │   │   ├── bookingConfirmation.html
  ├── package.json
  ├── .env.example
  ├── README.md

## Notes

- `client/` contains the public-facing UI, CSS, JS, and pages.
- `server/` contains backend API, database models, business logic, services, middleware, and email templates.
- `public/` can serve static assets and fallback files for deployment.
- `.env.example` should list required environment variables without secrets.
- `README.md` should document setup, architecture, and deployment steps.
